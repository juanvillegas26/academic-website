---
layout: course
title: "Power Electronics (Electrónica de Potencia)"
course_id: "EPW103"
description: >
  A theoretical-practical engineering course covering the analysis, modeling, simulation, design, 
  and implementation of power electronic converters (DC/DC, DC/AC). Topics include power drivers, 
  power factor correction (PFC), modulation strategies, and closed-loop control techniques for industrial energy management.
instructor: "Prof. Juan Pablo Villegas Ceballos"
year: 2026
term: 1
location: "Faculty of Engineering, ITM"
time: "68 Contact Hours (34 Theoretical-Practical + 34 Practical) | 136 Independent Study Hours"
prerequisites:
  - "Modern Physics (Física Moderna)"

schedule:
  - week: "1-2"
    date: "Feb 2 - Feb 9"
    topic: "Diagnostic Assessment & Introduction to Power Driver Circuits"
    description: >
      Diagnostic evaluation of prerequisite physics and circuit fundamentals (0%). 
      Analysis, design, and experimental validation of power drivers and gate-drive isolation circuits for power semiconductors.
    materials:
      - name: "Diagnostic Assessment Guidelines"
        url: "/assets/pdf/diagnostic_assessment.pdf"
      - name: "Practice 1 - Power Semiconductor Drivers"
        url: "/assets/pdf/lab1_power_drivers.pdf"

  - week: "3-7"
    date: "Feb 16 - Mar 16"
    topic: "Non-Isolated & Isolated DC/DC Converter Topologies"
    description: >
      Structure, operation, and steady-state analysis of non-isolated (Buck, Boost, Buck-Boost, Cuk) 
      and isolated DC/DC converters. Open-loop design, power factor correction (PFC) methods, and simulation validation.
    materials:
      - name: "Practice 2 - Open-Loop DC/DC & DC/AC Converters"
        url: "/assets/pdf/lab2_open_loop_converters.pdf"
      - name: "Interactive Buck/Boost Simulator"
        url: "https://juanpablovillegas.github.io/simulations/dcdc-converter.html"

  - week: "8-10"
    date: "Mar 23 - Apr 6"
    topic: "DC/AC Inverter Topologies & Modulation Techniques"
    description: >
      Inverter topologies (single-phase and three-phase) and modulation strategies (PWM/SPWM). 
      Harmonic reduction, filter design, and energy conversion applications.
    materials:
      - name: "Lecture Notes - Modulation Strategies"
        url: "/assets/pdf/modulation_techniques.pdf"

  - week: "11-13"
    date: "Apr 13 - Apr 27"
    topic: "Dynamic Modeling & Closed-Loop Control of Power Converters"
    description: >
      Small-signal modeling, transfer function derivation, and feedback control techniques applied to 
      DC/DC and DC/AC power converters to meet specific control objectives.
    materials:
      - name: "Practice 3 - Modeling & Control of DC/DC Converters"
        url: "/assets/pdf/lab3_control_dcdc.pdf"
      - name: "Practice 4 - Modeling & Control of DC/AC Converters"
        url: "/assets/pdf/lab4_control_dcac.pdf"

  - week: "14-15"
    date: "May 4 - May 11"
    topic: "Industrial Application Case Study (ABP)"
    description: >
      Individual problem-based learning (PBL) assessment focusing on an industrial application scenario. 
      Students select, design, simulate, and justify converter solutions based on technical, environmental, and ethical constraints.
    materials:
      - name: "Industrial Application Case Study Guide"
        url: "/assets/pdf/industrial_case_study.pdf"

  - week: "16-17"
    date: "May 18 - May 25"
    topic: "Final Course Project Defense & Portfolio Evaluation"
    description: >
      Final oral presentation, experimental demonstration, and technical portfolio defense of a fully functional 
      power converter prototype developed through Project-Based Learning (PBL).
    materials:
      - name: "Final PBL Project Guidelines & Rubric"
        url: "/assets/pdf/pbl_final_project_rubric.pdf"
---

## Course Overview

The **Power Electronics** (*Electrónica de Potencia*) course provides students in Electronic Engineering with the skills needed to analyze, model, simulate, design, and implement power electronic converters to optimize electrical energy flow in industrial contexts. 

### Key Learning Outcomes (ABET Alignment)
- **RA1 (High Contribution - A):** Ability to identify, formulate, and solve complex engineering problems by applying principles of engineering, science, and mathematics.
- **RA2 (High Contribution - A):** Ability to apply engineering design to produce solutions that meet specified needs with consideration of public health, safety, and welfare, as well as global, cultural, social, environmental, and economic factors.
- **RA3 (High Contribution - A):** Ability to develop and conduct appropriate experimentation, analyze and interpret data, and use engineering judgment to draw conclusions.
- **RA7 (High Contribution - A):** Ability to acquire and apply new knowledge as needed, using appropriate learning strategies (Autonomous Learning).

---

## Course Information

- **Course Code:** EPW103
- **Academic Program:** Electronic Engineering (Ingeniería Electrónica)
- **Faculty:** Faculty of Engineering
- **Credits:** 3 (68 Contact Hours + 136 Independent Study Hours)
- **Prerequisites:** Modern Physics (Física Moderna)
- **Modality:** On-campus / In-person

---

## Recommended Software & Laboratory Tools

- **Simulation Software:** PSIM, Multisim, Proteus
- **Hardware & Instruments:** Digital Oscilloscopes, Power Semiconductors (MOSFETs, IGBTs, Diodes), Isolation Transformers, Gate Driver Modules, LCR Meters.

---

## Grading Scheme

| Assessment Strategy | Weight (%) | Description & Instrumentation |
| :--- | :---: | :--- |
| **Diagnostic Prerequisites Assessment** | **0%** | Diagnostic test on physics and circuit prerequisites (Formative). |
| **Experimental Laboratory Practices** | **50%** | **4 Practical Labs @ 12.5% each** covering Gate Drivers, Open-Loop DC/DC & DC/AC Converters, and Closed-Loop Control of DC/DC & DC/AC Converters. [cite_start]Evaluated via simulation, hardware assembly, and technical reports[cite: 105]. |
| **Industrial Case Study (ABP)** | **20%** | [cite_start]Individual Problem-Based Learning assessment on an industrial application scenario, combining written design calculations, simulation, and oral technical defense[cite: 109]. |
| **Final PBL Course Project** | **20%** | Collaborative team project involving problem formulation, topology selection, simulation, hardware prototype implementation, and final oral defense with rubric evaluation. |
| **Independent Work & Portfolio** | **10%** | [cite_start]Cumulative evidence portfolio containing literature reading reports (datasheets/manuals), commented simulations, and self-assessments[cite: 109]. |

---

## Textbooks & References

### Books
- Rashid, M. H., González, M. H. R. V., & Fernández, P. A. S. (2004). *Electrónica de potencia: Circuitos, dispositivos y aplicaciones*. [cite_start]Pearson Educación[cite: 116, 117].
- Hart, D. W. (2011). *Power Electronics*. [cite_start]Tata McGraw-Hill Education[cite: 118].
- Erickson, R. W., & Maksimovic, D. (2001). *Fundamentals of Power Electronics*. [cite_start]Springer[cite: 119].
- Mohan, N., & Undeland, T. M. (2007). *Power Electronics: Converters, Applications, and Design*. [cite_start]John Wiley & Sons[cite: 120].
- Mohan, N. (2003). *First Courses on Power Electronic and Drives*. [cite_start]MNPERE, Minneapolis[cite: 121].
- Rashid, M. H. (2012). *Spice for Power Electronics and Electric Power*. [cite_start]CRC Press[cite: 122].

### Specialized Databases & Journals
- [cite_start]IEEE Xplore, ScienceDirect, Taylor & Francis, MDPI[cite: 138, 139].
- [cite_start]*IEEE Transactions on Power Electronics* / *IEEE Robotics and Automation Magazine*[cite: 126].
