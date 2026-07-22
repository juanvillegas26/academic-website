---layout: course
title: Computer-Aided Electronic Circuit and System Design
course_id: 530202016-530202028
description: >
  An applied course focused on the analysis, simulation, and implementation of 
  electronic circuits and systems using CAD tools. Students develop a fully functional 
  electronic prototype in pairs, integrating analog and digital stages, safety protections, 
  thermal management, custom PCB design, and mechanical enclosures.
instructor: Prof. Juan Pablo Villegas Ceballos
year: 2026
term: Spring (2026-1)
location: Campus Fraternidad / Robledo, ITM
time: Scheduled according to academic calendar
schedule:
  - week: 1-2
    date: Feb 2 - Feb 9
    topic: Introduction to the Electronic Design Process
    description: >
      Project scope definition (team/pair selection), reading schematic diagrams, datasheet analysis, 
      and structuring the Process Portfolio.
    materials:
      - name: Course Syllabus
        url: /assets/pdf/syllabus_circuit_design.pdf
      - name: Project Guidelines
        url: /assets/pdf/project_guidelines.pdf

  - week: 3-4
    date: Feb 16 - Feb 23
    topic: Circuit Architecture & Analog/Digital Integration
    description: >
      Designing functional blocks combining analog sensors, power stages, and microcontroller 
      interfaces. Operating limits and component selection.
    materials:
      - name: Lecture Notes - Analog Stages
        url: /assets/pdf/lecture_analog_stages.pdf

  - week: 5-6
    date: Mar 2 - Mar 9
    topic: Circuit Simulation & SPICE Validation
    description: >
      Verifying operating points, transient response, and frequency behavior using CAD software 
      (Multisim / Altium / KiCAD). Tolerance and failure analysis.
    materials:
      - name: Simulation Lab Guide
        url: /assets/pdf/lab_simulation.pdf
      - name: Interactive Circuit Simulator
        url: https://juanpablovillegas.github.io/simulations/circuit-analysis.html

  - week: 7-8
    date: Mar 16 - Mar 23
    topic: Electrical Safety & Protection Circuits
    description: >
      Implementing overcurrent, overvoltage, and reverse polarity protections. Electrical safety 
      standards for prototype assembly.
    materials:
      - name: Protection Circuits Guide
        url: /assets/pdf/protections_guide.pdf

  - week: 9-11
    date: Mar 30 - Apr 13
    topic: Professional Printed Circuit Board (PCB) Design
    description: >
      Component footprints, routing strategies, ground plane placement, Design Rule Checking (DRC), 
      and manufacturing output file generation (Gerber/NC Drill).
    materials:
      - name: PCB Design Rules
        url: /assets/pdf/pcb_design_rules.pdf

  - week: 12
    date: Apr 20
    topic: Thermal Management in Electronics
    description: >
      Calculating power dissipation in semiconductor devices, heatsink selection, airflow considerations, 
      and operating temperature limits.
    materials:
      - name: Thermal Analysis Sheet
        url: /assets/pdf/thermal_analysis.pdf

  - week: 13-14
    date: Apr 27 - May 4
    topic: Mechanical Enclosure & 3D Integration
    description: >
      Designing 3D-printed/custom enclosures, connector alignment, mechanical mounting, and physical ergonomics.
    materials:
      - name: CAD Enclosure Design
        url: /assets/pdf/enclosure_design.pdf

  - week: 15
    date: May 11
    topic: User Interfaces & Peripherals
    description: >
      Integrating displays, visual indicators, user controls, and peripheral communication.
    materials:
      - name: UI Design Notes
        url: /assets/pdf/user_interfaces.pdf

  - week: 16
    date: May 18
    topic: Assembly, Soldering & Testing
    description: >
      Hardware soldering, signal continuity checks, system-level debugging, and full operational testing.
    materials:
      - name: Testing & Validation Protocol
        url: /assets/pdf/testing_protocol.pdf

  - week: 17
    date: May 25
    topic: Final Project Presentation & Portfolio Review
    description: >
      Final prototype demonstration, delivery of the Process Portfolio, and evaluation.
---

## Course Overview

This course provides a practical, project-based approach to designing and manufacturing electronic hardware. Students will:

- Master the end-to-end electronic design workflow from concept to physical prototype.
- Utilize CAD tools for SPICE simulation and multi-layer PCB layout.
- Apply thermal management and electrical safety standards to real-world hardware.
- Develop a complete **Process Portfolio** documenting design decisions, simulations, and experimental validation.

## Prerequisites

- Electric Circuits I & Lab
- Analog Electronics & Lab

## Recommended Tools & Software

- **Schematic & PCB Capture:** KiCAD / Altium Designer / Multisim
- **Simulation:** LTspice / Multisim
- **3D Modeling:** Fusion 360 / SolidWorks

## Grading Breakdown

- **Simulation & Design (Week 6):** 20%
- **PCB Design & Gerbers (Week 11):** 20%
- **Thermal & Safety Analysis (Week 12):** 15%
- **Functional Prototype & Hardware (Week 16):** 25%
- **Final Process Portfolio & Documentation (Week 17):** 20%
