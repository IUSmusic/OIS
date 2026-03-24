
# SolarSynth

SolarSynth is a dual-engine instrument that combines a solar field synthesiser with a DMS-inspired rhythm engine.

## Current architecture

### SolarSynth engine
- Helio, Radio, and Plasma field synthesis
- Morph and Morph Lock
- Field Hold and Sustain
- Arpeggiator
- Filter, EQ, delay, reverb, bass, stereo width, motion, and depth
- Preset save and load
- Master output recording and WAV export
- Experimental external audio input modulation and pass-through
- File input blending into the field engine

### DMS rhythm engine
- Three independent sequencer tracks
- Per-track soundbank voice generation
- Per-track metronome behavior
- Per-track delay, reverb, and drive behavior
- Optional per-track mode switching between DMS bank, synth, and hybrid routing

### Routing and multi-track synth support
- Master synth track fed from the SolarSynth engine
- Three optional synth-capable lanes driven by sequencer routing
- Routing matrix for sequencer-to-synth sends
- Shared monitoring values for future top-row gauges on the main UI

## Included backend work
- Solar field synth engine with Helio, Radio, and Plasma behaviour
- Preset save and load
- Morph Lock, sustain, field hold, arpeggiator, recording, and WAV export
- Stereo input bus support and external input analysis
- DMS-inspired three-track sequencer backend
- Optional sequencer routing into synth lanes and hybrid routing backend
- Multi-lane synth backend with master synth lane plus optional sequencer-driven synth lanes

## Included main UI work
- Split UI into **Live** and **Settings** views
- Live view now matches the agreed architecture more closely:
  - top-row status gauges
  - master track for synth input
  - official-style monitoring track with live scope
  - three DMS sequencer track overviews
  - transport and recording controls on the main page
- Settings view keeps detailed synth controls off the main performance page
- Settings controls use compact bar-style vertical sliders instead of a wall of rotary knobs
- Morph response and slider drag feel are slightly more sensitive than before

# Documentation Pack

This folder contains the formal documentation set for the Solar and Plasma Synthesiser project.

The documentation is written for repository use, internal planning, investor review, and technical implementation. The language is intentionally formal and consistent so it can serve as the basis for official GitHub documentation.

## Document list

1. `01_Project_Charter.md`
2. `02_Product_Requirements_Document.md`
3. `03_System_Architecture.md`
4. `04_User_Interface_and_Interaction_Specification.md`
5. `05_Audio_and_Data_Engine_Specification.md`
6. `06_Demo_Version_Specification.md`
7. `07_Software_Product_Specification.md`
8. `08_Implementation_Roadmap.md`
9. `09_GitHub_Documentation_and_Release_Guide.md`
10. `10_References_and_Data_Sources.md`

## Purpose

The project aims to create a playable software synthesiser inspired by helioseismology, solar radio phenomena, and plasma behaviour. The instrument uses real scientific data where appropriate, and combines it with a controlled synthesis engine, expressive touch interaction, MIDI performance, and DMS-inspired visual language.

## Document use

- The charter establishes the project purpose and scope.
- The requirements document defines the product goals and user needs.
- The architecture and engine specifications define how the product should be built.
- The user interface document defines the interaction model.
- The demo and software specifications separate the GitHub release from the fuller product.
- The roadmap defines delivery stages.
- The documentation guide explains how these files should be presented in the repository.
- The references file records the scientific and technical basis for the work.

## Working project name

Until a final brand name is chosen, these documents use the working title **Solar and Plasma Synthesiser**.


**I/US Source-Available License 1.0**

Copyright (c) 2026 Pezhman Farhangi  
I/US Music
