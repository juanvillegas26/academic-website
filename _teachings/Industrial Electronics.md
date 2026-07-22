---
layout: course
title: Industrial Electronics
course_id: 530304011
description: >
  A theoretical-practical course covering the analysis, design, simulation, and implementation of 
  power electronic systems for industrial process control. Students study power semiconductor 
  devices (IGBT, MOSFET, TRIAC, SCR), power converter topologies (AC/DC, AC/AC, DC/DC, DC/AC), 
  modulation techniques (PWM/SPWM), and safe industrial control operations.
instructor: Prof. Juan Pablo Villegas Ceballos
year: 2026
term: 1
location: Faculty of Engineering, ITM
time: 68 Contact Hours (34 Theory + 34 Lab) | 136 Independent Study Hours
prerequisites:
  - "Field Physics and Laboratory (Física de Campos y Laboratorio)"

schedule:
  - week: 1-2
    date: Feb 2 - Feb 9
    topic: Diagnostic Assessment & Introduction to Power Semiconductors
    description: >
      Assessment of prerequisite knowledge via an un-graded lab on uncontrolled rectifiers[cite: 3653].
      Fundamentals of power semiconductor switches (Diodes, BJTs, MOSFETs, IGBTs, SCRs, TRIACs) [cite: 3651] and electrical safety standards[cite: 3651].
    materials:
      - name: Diagnostic Lab Guide & Technical Writing Guidelines
        url: /assets/pdf/diagnostic_lab.pdf

  - week: 3-5
    date: Feb 16 - Mar 2
    topic: Controlled Rectification & AC/DC Converters
    description: >
      Single-phase and three-phase controlled rectifiers, phase control, and industrial DC motor drive applications[cite: 3651].
    materials:
      - name: Practice 1 - Controlled Rectifiers
        url: /assets/pdf/lab1_controlled_rectifiers.pdf
      - name: Problem-Based Case Study 1
        url: /assets/pdf/case1_ac_dc.pdf

  - week: 6-8
    date: Mar 9 - Mar 23
    topic: AC/AC Voltage Controllers & Cycloconverters
    description: >
      AC voltage regulation, phase-angle control, cycle control, and applications in heating/lighting regulation.
    materials:
      - name: Practice 2 - AC/AC Converters
        url: /assets/pdf/lab2_ac_ac_converters.pdf
      - name: Problem-Based Case Study 2
        url: /assets/pdf/case2_ac_ac.pdf

  - week: 9-12
    date: Mar 30 - Apr 20
    topic: DC/DC Converters & PWM Modulation Techniques
    description: >
      Buck, Boost, and Buck-Boost topologies. Pulse-Width Modulation (PWM) strategies [cite: 3651] for switching power supplies and battery chargers[cite: 3653].
    materials:
      - name: Practice 3 - DC/DC Converters & PWM
        url: /assets/pdf/lab3_dcdc_converters.pdf
      - name: Interactive Buck/Boost Simulator
        url: https://juanpablovillegas.github.io/simulations/dcdc-converter.html

  - week: 13-15
    date: Apr 27 - May 11
    topic: DC/AC Inverters & SPWM Motor Drives
    description: >
      Single-phase and three-phase inverters, Sinusoidal PWM (SPWM) modulation [cite: 3651], AC motor speed control , and renewable energy grid integration[cite: 3644].
    materials:
      - name: Practice 4 - DC/AC Inverters & AC Drives
        url: /assets/pdf/lab4_inverters.pdf

  - week: 16-17
    date: May 18 - May 25
    topic: Final Project Presentation & Portfolio Defense
    description: >
      Integration, oral defense, and experimental demonstration of the industrial power converter prototype developed via Project-Based Learning (PBL)[cite: 3653].
    materials:
      - name: Final Project Guidelines & Rubric
        url: /assets/pdf/pbl_final_project.pdf
---

## Course Overview

[cite_start]The **Industrial Electronics** course [cite: 3638, 3640] [cite_start]equips students in Electronic Automation Technology [cite: 3638, 3640] [cite_start]with the theoretical and practical skills required to analyze, design, simulate, and implement power conversion systems for industrial automation[cite: 3640, 3651]. Key learning outcomes include:

- [cite_start]Mastering physical operating principles of power semiconductor switches[cite: 3651].
- [cite_start]Designing and simulating AC/DC, DC/DC, AC/AC, and DC/AC converter topologies using PSIM, Multisim, and Proteus[cite: 3651, 3653].
- [cite_start]Implementing physical hardware prototypes in laboratory settings following industrial safety regulations[cite: 3651, 3653].
- [cite_start]Applying Problem-Based Learning (PBL) to design real-world solutions (e.g., motor speed controllers, battery chargers, regulated power supplies)[cite: 3653].

## Course Information

- [cite_start]**Course Code:** 530304011 [cite: 3638]
- [cite_start]**Academic Program:** Electronic Automation Technology (Technology in Industrial Automation) [cite: 3638, 3640]
- [cite_start]**Credits:** 3 (68 Contact Hours + 136 Independent Study Hours) [cite: 3638]
- [cite_start]**Prerequisites:** Field Physics and Laboratory [cite: 3638]

## Recommended Software & Tools

- [cite_start]**Simulation Tools:** PSIM, Multisim, Proteus, OrCAD [cite: 3651, 3653]
- [cite_start]**Laboratory Hardware:** Power electronics modules, digital oscilloscopes, multimeters, DC/AC motors [cite: 3653]

## Grading Scheme

- [cite_start]**Laboratory Experiential Learning (4 Practical Labs @ 10% each):** 30% [cite: 3653, 3655]
- [cite_start]**Problem-Based Learning Case Studies (4 Individual Case Studies @ 10% each):** 30% [cite: 3653, 3655]
- [cite_start]**Final Course Project (PBL Prototype & Oral Presentation):** 20% [cite: 3653, 3655]
- [cite_start]**Independent Learning & Portfolio (Pre-reports, Datasheet Analysis & Self-Assessment):** 10% [cite: 3653, 3655]
- [cite_start]**Diagnostic Prerequisites Assessment:** 0% (Formative Feedback) [cite: 3653, 3655]

## Textbooks & References

- Boylestad, R. L., & Nashelsky, L. (2003). *Electronic Devices and Circuit Theory*. [cite_start]Pearson Education[cite: 3657].
- Hart, D. W. (2001). *Power Electronics*. [cite_start]McGraw-Hill / Pearson Education[cite: 3658].
- Mohan, N., Undeland, T. M., & Robbins, W. P. (2009). *Power Electronics: Converters, Applications, and Design*. [cite_start]Wiley / McGraw-Hill[cite: 3659].
- Rashid, M. H. (2004). *Power Electronics: Circuits, Devices, and Applications*. [cite_start]Pearson Education[cite: 3660].
