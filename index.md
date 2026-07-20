---
layout: default
title: Welcome to Raptor's Pilot Preparation Notes
---
# Raptor's Pilot Preparation Notes

This website is dedicated for study prepration for **Cathay Pacific Cadet Pilot Programme:** The cadet pathway currently requires a **Hong Kong Permanent Identity Card**. See [eligibility](interview_prep/eligibility.md) before you invest months in prep. Process details change by recruitment cycle — always confirm on [Cathay careers](https://careers.cathaypacific.com/en/careers/jobs/hong-kong/cadet-pilot-programme-29631).

## Sections

Here are the main sections of this website:

| Track | Start here |
| --- | --- |
| **Cathay cadet interview** | [Interview preparation hub](interview_prep/index.md) - contain information for Cadet Pilot interview |
| **CASA PPL theory exam** | [Preparation for PPL Exam](casa_ppl_exam/ppl_toc.md) - contain practical aviation knowledge |
| **Shared resources** | [Useful resources](useful_resources/resources.md) - collected useful resources across the Internet |

---

### Aviation Weather of Hong Kong International Airport (VHHH)

METAR: 
<textarea readonly id="txt_metar" class="textarea_weather"></textarea>

TAF:
<textarea readonly id="txt_taf" class="textarea_weather"></textarea>

<script>
// TAF
fetch('https://dev.yourappapp.com/weather/?type=taf')
  .then(response => response.text())
  .then(html => {
    document.getElementById('txt_taf').innerHTML = html;
  })
  .catch(error => console.warn('Error loading TAF:', error));

// METAR
fetch('https://dev.yourappapp.com/weather/')
  .then(response => response.text())
  .then(html => {
    document.getElementById('txt_metar').innerHTML = html;
  })
  .catch(error => console.warn('Error loading METAR:', error));

</script>

---

### About Me

Highly analytical and disciplined professional with a Master’s in Multimedia & Entertainment Technology and ongoing PhD research in Artificial Intelligence and Linguistics. Over 10 years as Assistant Professor mentoring students in design, technology, and collaborative projects. Proven leadership in managing technical teams and delivering complex initiatives under tight timelines as the co-founder of my digital agency. Passionate about aviation and committed to the highest standards of safety, precision, and crew resource management as a future Cathay Pacific pilot. My favourite aircraft is Airbus A330-300. No actual flight hours but 100+ hours in flight simulator. 

[Flight Path of my Cessna 172 Skyhawk Cargo ✈️](flight_path/)

---

### Disclaimer

Content on this site may contain errors or reflect past recruitment cycles. Use it for study support only; verify requirements with **Cathay Pacific**, **HKCAD**, and current official publications before applying.

### Contribution

To contribute (GitHub and Markdown), see the [repository](https://github.com/shivanraptor/pilot-ppl-notes).
