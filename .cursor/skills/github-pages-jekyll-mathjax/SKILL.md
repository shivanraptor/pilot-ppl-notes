---
name: github-pages-jekyll-mathjax
description: >-
  Renders LaTeX-style math on static Jekyll sites (e.g. GitHub Pages) when Markdown
  uses $...$ and $$...$$ but formulas appear as raw TeX. Use when GitHub Pages or
  Jekyll HTML shows broken or plain-text math, or when adding MathJax/KaTeX to a
  site layout. Covers MathJax 3 config, delimiter choice, and interaction with
  fenced code and Mermaid blocks.
---

# GitHub Pages / Jekyll: Math rendering

## Problem

Jekyll converts Markdown to HTML but does **not** ship a math renderer. Delimiters such as `$...$` and `$$...$$` stay as literal text in the browser unless a client-side library (or a build-time step) processes them.

## Solution (this project)

Load **MathJax 3** from a CDN in the shared layout (e.g. `_layouts/default.html`) **after** setting `window.MathJax` so the loader picks up configuration.

### Configuration pattern

- **Inline math:** `$...$` and `\(...\)`
- **Display math:** `$$...$$` and `\[...\]`
- **`processEscapes: true`** so escaped dollars in prose behave predictably.
- **`options.skipHtmlTags`:** include `pre` and `code` so **fenced code** and **Mermaid** ` ```mermaid ` blocks are not parsed as math.

### Script order

1. Synchronous inline `<script>` that assigns `window.MathJax = { tex: {...}, options: {...} }`.
2. Then `<script async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">` (or equivalent bundle).

Wrong order (loading MathJax before config) prevents options from applying.

### Layout CSS (optional)

Wide display equations can overflow on small screens. Add:

```css
mjx-container {
  overflow-x: auto;
  overflow-y: hidden;
  max-width: 100%;
}
```

## Kramdown caveat

In table cells or prose, **underscores** inside math (e.g. `CA_{close}`) can sometimes be interpreted as Markdown emphasis before MathJax runs. If subscripts render as italics or broken HTML, escape underscores in the Markdown source for those tokens or adjust the cell markup.

## Alternatives

- **KaTeX:** faster, smaller subset of LaTeX; swap CDN scripts and use its auto-render or manual API.
- **Kramdown `math_engine`:** can emit markup for math; you still need a compatible client script or build step for the published site.

## Reference implementation

See `_layouts/default.html` in this repository for the live MathJax block added for `pilot-ppl-notes` / GitHub Pages.
