# 🌱 Smart Modular Indoor Farming Pods for Urban Homes

> A comprehensive engineering project management plan for designing, prototyping, and validating a compact, sensor-equipped indoor farming system tailored for urban apartments.

![Project Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Course](https://img.shields.io/badge/Course-Engineering%20Project%20Management-blue)
![University](https://img.shields.io/badge/University-Northeastern%20University-red)

---

## 📋 Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Product Description](#product-description)
- [Project Phases](#project-phases)
- [Team Members](#team-members)
- [Project Organization](#project-organization)
- [Key Deliverables](#key-deliverables)
- [Risk Analysis](#risk-analysis)
- [Financial Summary](#financial-summary)
- [Repository Structure](#repository-structure)
- [Tools & Technologies](#tools--technologies)
- [Critical Success Factors](#critical-success-factors)
- [Acknowledgements](#acknowledgements)

---

## Overview

This repository contains the complete project management documentation for the **Smart Modular Indoor Farming Pods** — a 12-week academic project completed as part of the Engineering Project Management (EPM) course at Northeastern University, Fall 2025, under the guidance of **Dr. Andrei Guschin**.

The project applies core EPM principles including Work Breakdown Structures (WBS), PERT analysis, Gantt scheduling, FMEA-based risk quantification, Earned Value Management, and structured monitoring and control frameworks to plan the development of a real-world IoT product.

---

## Problem Statement

Urban living spaces are shrinking while demand for fresh, locally grown food continues to rise. In cities like Boston, harsh winters restrict outdoor gardening for up to four months annually. Existing indoor gardening solutions are often expensive, bulky, or overly complex for first-time growers.

**Our solution:** A compact, modular, sensor-equipped indoor farming pod paired with an intuitive companion mobile app that provides real-time growing guidance — making year-round indoor cultivation accessible to anyone.

---

## Product Description

The Smart Modular Indoor Farming Pod is a self-contained, vertically expandable unit featuring:

- **Environmental Sensors** — moisture, humidity, temperature, and light monitoring via Arduino/ESP32 microcontrollers
- **Adjustable LED Grow Lights** — full-spectrum, energy-efficient lighting (< 15W per pod)
- **Modular Frame Design** — stackable 1 sq. ft. footprint supporting 1–5 pod configurations
- **Companion Mobile App** — real-time watering reminders, nutrient alerts, harvest suggestions, and sensor data visualization
- **Dual Growing Modes** — supports both soil-based and hydroponic configurations

Target crops include herbs (basil, cilantro), leafy greens (lettuce, microgreens), and small vegetables (peppers, cherry tomatoes) — all under 14–16 inches at maturity.

---

## Project Phases

| Phase | Description | Duration |
|-------|-------------|----------|
| **Phase 1** | Research & Planning — Market research, feasibility analysis, technical requirements | Weeks 1–3 |
| **Phase 2** | Design & Integration — Mechanical design, sensor selection, software prototype | Weeks 4–6 |
| **Phase 3** | Testing & Validation — Prototype assembly, plant trials, data collection | Weeks 7–9 |
| **Phase 4** | Integration, Evaluation & Finalization — Iteration, final reporting, presentation | Weeks 10–12 |

> **Key Scheduling Decision:** Plant trials were deliberately initiated in Week 8 (before full prototype completion) to ensure 3–4 weeks of biological validation data — the project's most strategically important scheduling choice.

---

## Team Members

| Name | Role |
|------|------|
| **Danyelle Veillard** | Team Member |
| **Ashwini Mahadevaswamy** | Team Member |
| **Shamsheer Hussain** | Team Member |
| **Madison Rogers** | Team Member |
| **Mohit Athipedu** | Team Member |

---

## Project Organization

The team is structured into **five functional areas**, each with clear ownership:

```
                        Project Manager
                              │
        ┌─────────┬──────────┼──────────┬──────────────┐
        │         │          │          │              │
   Hardware    Software   Agriculture  Risk &      Business &
   Dev Team   & App Dev   & Environ.  Quality Mgmt Operations
```

- **Hardware Development** — Enclosure design, sensor integration, electronics assembly
- **Software & App Development** — Mobile app, data visualization, alert systems
- **Agriculture & Environmental Systems** — Plant species selection, growth optimization
- **Risk & Quality Management** — FMEA, reliability testing, QA protocols
- **Business & Operations** — Procurement, pilot coordination, market validation

---

## Key Deliverables

This repository includes the following project management artifacts:

| # | Document | Description |
|---|----------|-------------|
| 1 | Individual Project Idea | Initial concept proposal and ideation |
| 2 | Team Project Proposal | Collaborative project proposal with team alignment |
| 3 | Project Phases & Objectives | Detailed phase breakdown, success criteria, and assumptions |
| 4 | Org Structure & Network Diagram | Organization chart and communication infrastructure |
| 5 | WBS, Responsibility & Gantt Chart | Work breakdown, RACI-style matrix, and 12-week Gantt |
| 6 | Monitoring, Control & Financial Plan | KPIs, Earned Value Management, budgeting, and cost-benefit analysis |
| 7 | Final Project Plan (Consolidated) | Complete integrated project plan document |
| 8 | Final Project Plan (PDF) | Print-ready version of the consolidated plan |
| 9 | Project Presentation | Slide deck used for final project presentation |

---

## Risk Analysis

### Qualitative Analysis (5×5 Risk Matrix)
Risks were assessed on a Likelihood × Impact matrix and classified as High, Medium, or Low priority.

### Quantitative Analysis (FMEA)
Top risks ranked by **Risk Priority Number (RPN = Severity × Occurrence × Detection)**:

| Risk | Severity | Occurrence | Detection | RPN |
|------|----------|------------|-----------|-----|
| Prototype Design Rework | 6 | 7 | 5 | **210** |
| IoT Connectivity Issues | 8 | 6 | 4 | **192** |
| App Integration / CAD Compatibility | 7 | 5 | 5 | **175** |
| Plant Growth Variation | 7 | 6 | 4 | **168** |
| Data Loss / Sensor Logging | 7 | 4 | 6 | **168** |
| Budget Overrun | 8 | 4 | 5 | **160** |
| Team Member Unavailability | 5 | 5 | 6 | **150** |
| Sensor Supply Delays | 8 | 6 | 3 | **144** |
| Electronics / Microcontroller Issues | 7 | 5 | 4 | **140** |
| UX Problems | 6 | 7 | 3 | **126** |

---

## Financial Summary

| Category | Estimated Cost |
|----------|---------------|
| Materials & Tools | $310 |
| Personnel Effort Value | ~$4,338 |
| **Total Estimated Project Cost** | **~$4,648** |

### Break-Even Analysis
- **Retail Price per Pod:** $135
- **Manufacturing Cost per Pod:** $40
- **Contribution Margin:** $95
- **Break-Even Quantity:** 49 pods

---

## Repository Structure

```
Smart-Modular-Indoor-Farming-Pods/
│
├── README.md                                          # Project overview (this file)
├── LICENSE                                            # MIT License
├── .gitignore                                         # Git ignore rules
│
├── docs/                                              # Project documentation
│   ├── 01_Individual_Project_Idea.docx
│   ├── 02_Team_Project_Proposal.docx
│   ├── 03_Project_Phases_and_Objectives.docx
│   ├── 04_Org_Structure_and_Network_Diagram.docx
│   ├── 05_WBS_Responsibility_and_Gantt_Chart.docx
│   ├── 06_Monitoring_Control_and_Financial_Plan.docx
│   └── EPM_Project_Plan_Team_4_Fall_2025.docx
│
├── deliverables/                                      # Final outputs
│   ├── Final_Project_Plan_Farming_Pods.pdf
│   ├── Final_Project_Plan.pdf
│   └── Project_Presentation.pptx
│
└── assets/                                            # Images & diagrams (if extracted)
    └── (optional: org chart, WBS, Gantt, PERT images)
```

---

## Tools & Technologies

### Product Technologies
- **Microcontrollers:** Arduino / ESP32
- **Sensors:** DHT22 (humidity/temperature), soil moisture, light sensors
- **Lighting:** Full-spectrum LED grow strips (< 15W per pod)
- **Materials:** Acrylic, PVC, modular joints

### Project Management Tools
- **MS Project** — Timeline management, dependency tracking, critical path analysis
- **Trello** — Day-to-day task management and workflow visualization
- **OneDrive / Google Drive** — Centralized document repository
- **Jupyter Notebook (Python)** — Gantt chart generation

---

## Critical Success Factors

1. Functional prototype completed within 8 weeks and within budget
2. Successful plant growth for at least 2 varieties (leafy green + small vegetable)
3. Mobile app achieving ≥ 95% command execution rate
4. ≥ 80% positive feedback from 15–20 beta users in Boston
5. Modular design supporting 1–5 pod configurations without degradation
6. Cross-team issue resolution within 4 hours (critical) / 24 hours (standard)

---

## Acknowledgements

This project was completed as part of the **Engineering Project Management** course at **Northeastern University, College of Engineering**, Boston, MA — Fall 2025.

**Instructor:** Dr. Andrei Guschin

---

*This repository is intended for academic portfolio and showcase purposes.*
