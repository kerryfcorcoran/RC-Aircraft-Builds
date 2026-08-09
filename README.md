RC Aircraft Builds

Engineering build documentation for my RC aircraft projects.

This repository is intended to serve as a long-term technical archive for aircraft from multiple manufacturers, with each project organized by:

Manufacturer → Aircraft Model / Family → Version → Build

Each physical aircraft build can maintain its own manufacturing records, hardware configuration, assembly notes, ArduPilot configuration, flight-test history, engineering analysis, media, and downloadable resources.

Project Website

The repository is published as a static website using GitHub Pages.

The root page acts as the main aircraft-project hub, with navigation into each manufacturer and aircraft family.

Repository Organization

The intended structure is:

/
├── index.html
├── README.md
│
└── aircraft/
    ├── flightory/
    │   ├── stallion/
    │   │   ├── v1/
    │   │   │   └── build-01/
    │   │   └── v2/
    │   │       └── build-01/
    │   │
    │   ├── super-stingray-vtol/
    │   ├── talon-1400/
    │   └── stork/
    │
    └── <future-manufacturer>/
        └── <aircraft-model>/
            └── <version>/
                └── <build>/

This structure allows multiple aircraft from the same manufacturer, multiple versions of the same model, and multiple physical builds of each version without mixing configuration or test data.

Current Aircraft Projects

Flightory

Stallion

Stallion VTOL V1

Build 01 — existing completed aircraft

Stallion VTOL V2

Build 01 — active build

Planned Flightory Aircraft

Super Stingray VTOL

Talon 1400

Stork

Additional manufacturers and aircraft will be added as future projects begin.

Per-Build Documentation

Each physical aircraft build can contain its own documentation areas:

build-01/
├── index.html
├── printing/
├── components/
├── assembly/
├── ardupilot/
├── flight-testing/
├── engineering/
├── media/
└── downloads/

3D Printing / Manufacturing

May include:

Individual printed components

Printer used

Filament / material

Slicer and slicer version

Wall count

Infill type and percentage

Orientation

Support settings

Part weight

Print time

Filament consumption

Reprints

Failed prints

Manufacturing notes

Slicer-specific requirements

Lessons learned

Components

May include:

Motors

ESCs

Servos

Flight controller

GPS / compass

Telemetry

Video system

Receiver

Batteries

Propellers

Wiring

Connectors

Antennas

Other avionics and hardware

Assembly

May include:

Airframe assembly

Adhesives

Fasteners

Wiring diagrams

Connector layouts

Component placement

Structural modifications

Custom parts

Repair and rework history

ArduPilot

May include:

Firmware version

Flight-controller configuration

Parameter files

QuadPlane / VTOL setup

Flight modes

Servo mappings

Motor mappings

Failsafe configuration

Calibration

Baseline PARAM files

Configuration-change history

Flight Testing

May include:

Ground-test records

Motor tests

Control-surface validation

Hover testing

QSTABILIZE testing

QLOITER testing

Forward-flight testing

Transition testing

Flight-test objectives

Results

Observations

Pass / Review / Fail disposition

Engineering Analysis

May include:

ArduPilot BIN logs

Flight-log analysis

Controller tuning

Yaw analysis

EKF analysis

Magnetic-interference analysis

Parameter comparisons

Configuration-change reports

Flight comparisons

Engineering assessment reports

Media

Images and diagrams may be stored directly in the repository.

Video is generally hosted externally, such as on YouTube, and embedded or linked from the appropriate build or flight-test page.

A typical media structure may be:

media/
├── printing/
├── assembly/
├── electronics/
├── ground-testing/
└── flight-testing/

Downloads

May include:

PARAM files

Manufacturing reports

Engineering reports

Configuration baselines

Wiring diagrams

Reference documents

Other project resources

Current Manufacturing Documentation

The active Stallion VTOL V2 Build 01 project includes a detailed 3D-printing manufacturing report with:

Part-by-part production data

Material consumption

Print times

Component weights

Printer assignments

Slicer configuration

Reprint history

Thin-wall settings

Manufacturing findings

The current primary slicer baseline is:

OrcaSlicer v2.4.2

Detect Thin Walls: Enabled where required

Wall Generator: Arachne for validated thin-wall components

Primary materials currently documented include:

Polymaker PolyLite LW-PLA

Overture PETG

Generic transparent PLA

Media Strategy

Images

Build photos, diagrams, wiring references, component-placement photos, damage documentation, and other still images can be stored directly in the GitHub repository.

Video

Flight-test and testing video should generally be hosted on a video platform such as YouTube and embedded into the corresponding build or flight-test page.

This avoids adding large video files to Git history while still keeping the video associated with the aircraft's engineering record.

Project Goals

The purpose of this repository is to maintain a reproducible engineering record rather than only a photo-based build log.

The documentation should preserve:

What was built

How it was built

Which hardware was installed

Which firmware and parameters were used

What changed between tests

What failed

What worked

Why a change was made

How the aircraft performed afterward

The goal is to make each aircraft easier to maintain, reproduce, troubleshoot, compare, and improve over time.

Project Status

Active and evolving

Aircraft, documentation, configuration, and test results in this repository may change as builds progress.

Disclaimer

These projects involve experimental RC aircraft and, in some cases, VTOL / autonomous-flight systems.

The information in this repository documents specific aircraft builds and test configurations. Anyone applying information from these projects to another aircraft is responsible for independently verifying the safety, suitability, legality, mechanical integrity, electrical configuration, software configuration, and operating procedures of their own aircraft.
