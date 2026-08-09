# Stallion VTOL V2

Build, manufacturing, configuration, and flight-test documentation for a
Flightory Stallion VTOL V2 aircraft.

This repository is being used to document the construction and development
of the aircraft, including 3D-printing records, hardware configuration,
ArduPilot setup, testing, tuning, and lessons learned during the build.

## Live Project Report

The current 3D-printing and manufacturing report is available here:

**https://kerryfcorcoran.github.io/stallion-vtol-v2/**

The report includes:

- Individual printed components
- Printer used for each component
- Filament/material
- Slicer and relevant slicer settings
- Print orientation and infill where recorded
- Individual component weight
- Print time
- Filament consumption
- Reprints and manufacturing notes
- Material totals
- Overall manufacturing statistics
- Lessons learned during printing

## 3D Printing

Printers used during the build include:

- Creality K1 Max — K1 White
- Creality K1 Max — K1 Orange
- Elegoo Neptune 2S

### Primary Slicer

[OrcaSlicer v2.4.2](https://github.com/OrcaSlicer/OrcaSlicer/releases/tag/v2.4.2)

Some thin-wall components require:

- **Detect Thin Walls:** Enabled
- **Wall Generator:** Arachne

This configuration was specifically validated for several of the boom
interface components.

### Primary Materials

- [Polymaker PolyLite LW-PLA](https://us.polymaker.com/products/polylite-lw-pla)
- [Overture PETG](https://overture3d.com/products/overture-petg)
- Transparent PLA for lighting components

LW-PLA is used primarily for lightweight aerodynamic structures, while PETG
is used for structural components, mounts, reinforcement pieces, and other
parts requiring greater durability.

## Manufacturing Documentation

The manufacturing report tracks both successful prints and significant
production findings.

This includes documenting:

- Failed or superseded prints
- Reprints
- Slicer-specific requirements
- Thin-wall behavior
- Support requirements
- Material selection
- Part weights
- Print duration
- Filament consumption
- Custom/replacement components

The intent is to maintain enough information to reproduce the aircraft and
avoid repeating problems discovered during the original build.

## Project Documentation

Additional documentation may be added to this repository as the project
progresses, including:

- Aircraft assembly
- Electronics and wiring
- Flight controller configuration
- ArduPilot parameters
- VTOL configuration
- Ground testing
- Hover testing
- QSTABILIZE / QLOITER testing
- Controller tuning
- Flight-test results
- Transition testing
- Engineering analysis

## Project Status

**Active development and flight testing**

The aircraft and its documentation are still evolving. Information in this
repository should therefore be considered part of an ongoing engineering
build record rather than a finalized construction manual.

## Disclaimer

This repository documents an experimental RC VTOL aircraft project.

The information provided here reflects the configuration, equipment,
manufacturing methods, and test results of this specific aircraft. Anyone
using this information for their own project is responsible for independently
verifying the suitability and safety of their aircraft, electronics,
software configuration, and operating procedures.

## Repository

GitHub repository:

**https://github.com/kerryfcorcoran/stallion-vtol-v2**

Live documentation:

**https://kerryfcorcoran.github.io/stallion-vtol-v2/**
