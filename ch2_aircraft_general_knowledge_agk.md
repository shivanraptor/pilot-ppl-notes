---
layout: default
title: Chapter 2 - Aircraft General Knowledge (AGK)
---
# Chapter 2 - Aircraft General Knowledge (AGK)

**Navigation:** [<- Previous Chapter 1](ch1_air_law.md) | [Overview](index.md) | Chapter 2 | [Next -> Chapter 3](ch3_flight_performance_and_planning.md)

These notes are exam-focused for CASA PPL AGK and aligned with FAA PHAK system knowledge where technically applicable. Use your aircraft POH/AFM as final authority for numbers, limitations, and procedures.

---

## 2.0 Terminology: POH and AFM

- **AFM (Airplane/Aircraft Flight Manual):** the approved flight manual containing aircraft-specific operating limitations, procedures, and performance data that pilots must comply with.
- **POH (Pilot's Operating Handbook):** the manufacturer handbook used in day-to-day operations; for most light aircraft, the POH includes the approved AFM sections and is commonly referred to as the aircraft's `AFM/POH`.
- **Why this matters for exam and flight:** if a generic rule conflicts with aircraft documentation, follow the approved `AFM/POH`, placards, and limitations for that specific aircraft.

---

## 2.1 Airframe, Structure, and Flight Controls

- **Major airframe groups**: fuselage, wings, empennage (horizontal/vertical stabilizers), landing gear, engine mount, control surfaces.
- **Primary controls**:
  - Ailerons -> roll
  - Elevator/stabilator -> pitch
  - Rudder -> yaw
- **Secondary/high-lift/drag devices**:
  - Flaps (plain/split/slotted/Fowler) increase lift and drag
  - Trim tabs reduce control force
- **Typical construction**:
  - Semi-monocoque metal/composite fuselage
  - Stressed skin, frames, stringers, spars, ribs
- **Structural terms**:
  - **Datum** for W&B
  - **Stations/arms**
  - Limit load vs ultimate load
  - Normal vs utility category limitations
- **Common failure risks**:
  - Corrosion, fatigue cracking, buckling, control cable wear, hinge damage.

### Visual references (primary and secondary controls)

**Primary flight controls (aileron, elevator, rudder):**

![Primary flight controls diagram](https://commons.wikimedia.org/wiki/Special:FilePath/ControlSurfaces.gif)

Source page: [Wikimedia Commons - ControlSurfaces.gif](https://commons.wikimedia.org/wiki/File:ControlSurfaces.gif)

**Secondary/high-lift and drag devices on wing (flaps, slats, spoilers, etc.):**

![Wing control surfaces and high-lift devices](https://commons.wikimedia.org/wiki/Special:FilePath/Control_surfaces_at_the_wing_of_a_plane.svg)

Source page: [Wikimedia Commons - Control surfaces at the wing of a plane.svg](https://commons.wikimedia.org/wiki/File:Control_surfaces_at_the_wing_of_a_plane.svg)

### Exam cues
- Know what each control does and opposite control combinations for coordinated turns.
- Understand flap effects on stall speed, drag, climb performance, and go-around behavior.

---

## 2.2 Piston Engine Fundamentals

- **Four-stroke cycle**: intake, compression, power, exhaust.
- **Engine layout**: opposed cylinders, crankshaft, camshaft, valves, spark plugs.
- **Power output factors**:
  - Mixture strength
  - RPM/manifold pressure (if CS prop)
  - Volumetric efficiency
  - Density altitude
- **Detonation vs pre-ignition**:
  - Detonation: uncontrolled rapid combustion after normal ignition.
  - Pre-ignition: charge ignites before spark event (hot spot).
  - Both can cause severe engine damage.
- **Shock cooling risk**: avoid excessive, abrupt CHT reductions in descent where applicable to type/SOP.

### Induction systems
- **Carburettor**: venturi, fuel metering, throttle butterfly, mixture control.
- **Fuel injection**: generally better distribution and less carb icing risk.
- **Carb icing**:
  - Possible in visible moisture and moderate temperatures, also in clear air with high humidity.
  - Greatest risk at partial power settings.
  - Symptoms: RPM drop (fixed pitch), roughness, MP drop (CS), possible EGT changes.
  - Action: carb heat ON, expect initial roughness/power loss before recovery.

### Ignition
- Magnetos are independent of aircraft electrical power.
- Dual magnetos improve efficiency/redundancy.
- Magneto check (run-up) verifies proper ignition system performance.

### Lubrication and cooling
- Oil functions: lubricate, cool, clean, seal, protect against corrosion.
- Cooling: air-cooled cylinder fins, baffles/cowl airflow, oil cooling contribution.
- Monitor oil pressure/oil temperature trends, not just single values.

---

## 2.3 Propellers

- **Fixed-pitch**:
  - Simple, lighter.
  - Climb prop: better acceleration/climb, lower cruise speed.
  - Cruise prop: better cruise, reduced climb performance.
- **Constant-speed**:
  - Governor varies blade angle to hold selected RPM.
  - Low pitch/high RPM for take-off and climb; high pitch/lower RPM for cruise efficiency.
- **Key terms**:
  - Blade angle, coarse/fine pitch, geometric vs effective pitch, slip.
- **Operational considerations**:
  - Overspeed response
  - Propeller control use sequence (follow POH)
  - Avoid operation in RPM/manifold pressure prohibited zones.

---

## 2.4 Fuel System and Fuel Management

- **Typical components**: tanks, vents, selectors, strainers/filters, drains, pumps (engine/electric), lines, gauges, engine control unit or carburettor.
- **Fuel contamination**:
  - Water, sediment, microbial contamination (storage dependent).
  - Sump drains preflight until clear sample.
- **Fuel grade/type discipline**:
  - Must match POH/AFM and placards.
  - Do not rely only on color/smell.
- **Fuel starvation vs fuel exhaustion**:
  - Starvation: fuel onboard but not reaching engine (mismanagement/system issue).
  - Exhaustion: no usable fuel remaining.
- **Balancing and feed management**:
  - Use recommended tank selection and switching intervals.
  - Avoid prolonged uncoordinated/slip conditions if prohibited with low fuel states.

### CASA exam-relevant points
- CASA workbook uses **AVGAS specific gravity 0.72 kg/L** in loading/fuel calculations.
- Fuel planning questions may reference **CASR Part 91 MOS** day VFR fuel policy.
- In exam scenarios, read whether operation assumptions are Part 91/other as stated.

---

## 2.5 Electrical System

- **Core components**: battery, alternator/generator, voltage regulator, bus bars, circuit breakers/fuses, master and avionics switches.
- **System types**: direct current (common in light GA), with alternator output and battery reserve.
- **Failure indications**:
  - Ammeter/voltmeter abnormal
  - Low-voltage annunciation
  - Radio/intercom degradation
- **Typical actions** (POH-specific): load shedding, alternator reset attempt if permitted, essential bus management, land as soon as practical if unresolved.

---

## 2.6 Vacuum/Pressure, Gyros, and Modern Avionics

- Traditional gyros may be powered by vacuum pump or electrically.
- **Gyroscopic principles**:
  - Rigidity in space
  - Precession
- **Classic gyro instruments**:
  - Attitude indicator
  - Heading indicator (directional gyro)
  - Turn coordinator
- **Common failures**:
  - Vacuum failure -> AI/HI unreliable (type-dependent)
  - Partial panel skills are essential.
- **Glass cockpit concept**:
  - Air data computer and AHRS feed PFD/MFD
  - Failure modes differ from round-dial systems; know reversionary procedures.

---

## 2.7 Pitot-Static Instruments and Errors

- **Airspeed Indicator (ASI)**: pitot (total pressure) minus static pressure -> dynamic pressure.
- **Altimeter**: static pressure converted to altitude; requires correct subscale setting (QNH in AUS ops).
- **Vertical Speed Indicator (VSI)**: rate of static pressure change.

### Blockage scenarios (high-yield)
- **Pitot blocked, drain open** -> ASI drops toward zero.
- **Pitot and drain blocked** -> ASI acts like altimeter (reads unreliable with altitude change).
- **Static blocked**:
  - Altimeter freezes
  - VSI zero
  - ASI under-reads in climb, over-reads in descent (typical behavior).

### Airspeed terminology
- IAS, CAS, EAS, TAS, GS.
- TAS increases with altitude for same IAS.

### Instrument/position errors
- Position error from static source location.
- Density/compressibility effects (mainly higher speed/altitude regimes).
- Lag and hysteresis in mechanical systems.

---

## 2.8 Magnetic Compass and Turning/Acceleration Errors

- Compass aligns with magnetic field, not true north.
- **Variation**: true vs magnetic.
- **Deviation**: local aircraft magnetic interference.
- **Turning error (UNOS in Southern Hemisphere)**:
  - Undershoot North, Overshoot South.
- **Acceleration error (ANDS in Southern Hemisphere)**:
  - Accelerate North, Decelerate South.
- Oscillation/dip/lag increase at higher latitudes and in turbulence.

---

## 2.9 Landing Gear, Brakes, and Hydraulics

- **Landing gear**: fixed or retractable, tricycle or tailwheel.
- **Brakes**: hydraulic disc brakes commonly used; independent toe brakes aid directional control.
- **Risks**:
  - Brake fade/overheat after heavy braking
  - Parking brake misuse on takeoff
  - Hydraulic leaks or soft pedal.
- For retractables (if applicable): extension systems, warning systems, emergency extension method.

---

## 2.10 Environmental, Ice/Anti-Ice, and Oxygen Basics

- Cabin heat often uses exhaust shroud heat exchanger; carbon monoxide risk requires vigilance.
- Ventilation and demist/defog systems are safety-critical in humid/rainy conditions.
- **Ice types**:
  - Induction ice (carb/filter/intake)
  - Airframe ice (leading edges)
  - Instrument/pitot ice
- **System language**:
  - Anti-ice prevents formation.
  - De-ice removes accumulation.
- **Oxygen** (if equipped): know legal/physiological triggers, equipment checks, and fire hazards.

---

## 2.11 AFM/POH Knowledge You Must Know for Exam and Flight Test

- **Limitations section**:
  - Airspeed limits (V-speeds and color arcs)
  - Powerplant limits (RPM/MP/temp/pressure)
  - Weight limits (MTOW, landing, baggage)
  - CG envelope and category restrictions.
- **Normal/abnormal/emergency procedures**:
  - Memory items vs checklist follow-up.
- **Performance charts**:
  - Takeoff/landing distance factors
  - Climb performance effects
  - Density altitude, wind, slope, surface corrections.
- **Systems section**:
  - Fuel usable/unusable
  - Electrical architecture
  - Hydraulic/pneumatic details
  - Emergency extension/alternate procedures.

### High-value memory set
- All relevant V-speeds for your training type.
- Fuel system capacities and unusable fuel.
- Oil limits, CHT/EGT limits (if listed), and key caution ranges.

---

## 2.12 Weight and Balance Link to AGK

- **Core formulae**:
  - Moment = Weight x Arm
  - CG = Total Moment / Total Weight
- **Concept checks**:
  - Basic Empty Weight usually includes unusable fuel and full operating fluids as defined by data source.
  - CG must remain in envelope at all flight stages (takeoff, en route, landing).
- **Operational impacts**:
  - Forward CG: higher stall speed tendency, higher control force, longer takeoff roll.
  - Aft CG: reduced stability, lower stall warning margin, possible control issues in flare/recovery.

---

## 2.13 Key Definitions and Practical Examples

- **Detonation:** abnormal, explosive combustion after normal ignition, causing high thermal/mechanical stress.
  - Example: high power with improper mixture/cooling in hot conditions can increase risk.
- **Pre-ignition:** mixture ignites before spark due to a hot spot.
  - Example: fouled/damaged plug or overheated component can trigger early ignition and rapid temperature rise.
- **Fuel starvation:** fuel onboard but not reaching engine.
  - Example: incorrect tank selection after switching or blocked vent.
- **Fuel exhaustion:** usable fuel depleted.
  - Example: inaccurate fuel planning plus headwind leads to empty selected tank and engine stoppage.
- **Static source blockage:** loss of correct static pressure feed to instruments.
  - Example: altimeter freezes and VSI reads zero; ASI behavior becomes misleading in climb/descent.

### Scenario: carb icing recognition

- Cruise at moderate power in humid conditions; RPM slowly falls and engine feels rough.
- Correct action: apply full carb heat, expect temporary roughness/power drop, monitor recovery, then reassess power/settings.

---
## 2.14 Common AGK Exam Traps

- Confusing fuel **quantity** problem with fuel **feed/selection** problem.
- Misreading ASI/static blockage scenarios.
- Forgetting density altitude effects on engine, prop, and wing together.
- Applying generic numbers instead of aircraft-specific POH values.
- Mixing true/magnetic/compass headings and signs for variation/deviation.
- Neglecting POH limitations for flap speeds and crosswind technique limits.

---

## 2.15 Rapid Revision Checklist (Pre-Exam)

- Can explain operation/failures of ASI, altimeter, VSI.
- Can diagnose carb icing and apply correct immediate actions.
- Can distinguish detonation vs pre-ignition and preventive handling.
- Can describe fixed vs constant-speed propeller operation and implications.
- Can compute basic W&B and interpret CG movement with fuel burn.
- Can state fuel contamination checks and fuel grade verification method.
- Can interpret compass turning/acceleration errors for Southern Hemisphere use.
- Can navigate POH sections quickly for limits, systems, and emergencies.

---

## References (Primary)

- FAA Pilot's Handbook of Aeronautical Knowledge (full handbook and chapter PDFs): https://www.faa.gov/regulations_policies/handbooks_manuals/aviation/phak
- FAA PHAK Chapter 7 Aircraft Systems: https://www.faa.gov/regulationspolicies/handbooksmanuals/aviation/phak/chapter-7-aircraft-systems
- FAA PHAK Chapter 9 Flight Manuals and Other Documents (AFM/POH concepts): https://www.faa.gov/regulationspolicies/handbooksmanuals/aviation/phak/chapter-9-flight-manuals-and-other-documents
- CASA RPL/PPL/CPL Aeroplane Workbook (exam assumptions and worked-method conventions): https://www.casa.gov.au/rpl-ppl-and-cpl-aeroplane-workbook

## References (Supplementary)

- CASA Day VFR syllabus pages (structure and competency framing): https://www.casa.gov.au/day-vfr-helicopters-syllabus
- CASA VFR guidance example copy (training/support reference, not legislation): https://www.kempseyflyingclub.com.au/Docs/Visual%20Flight%20Guide%202020.pdf

---

**Navigation:** [<- Previous Chapter 1](ch1_air_law.md) | [Overview](overview.md) | Chapter 2 | [Next -> Chapter 3](ch3_flight_performance_and_planning.md)

