# CRM Design Coding Workshop Slides

Slides from the CRM Design Coding Workshop (2023-09-26), presented by Joanne Chou and Karissa Whiting on simulations for Phase I CRM (Continual Reassessment Method) clinical trial design.

## Contents

- `CRM Design Coding Workshop 2023-09-26.pdf` — workshop slide deck

## Agenda

- Hackathon Announcements (Caroline Kostrzewa)
- Review of CRM Designs (Joanne Chou)
- Intro to Coding CRM Simulations & Coding Exercise (Joanne Chou & Karissa Whiting)

## Topics covered

- Phase I trial design objectives: toxicity characterization, Dose-Limiting Toxicity (DLT), Maximum Tolerated Dose (MTD)
- Rules-based (e.g. 3+3) vs. model-based (CRM) dose escalation designs, and their tradeoffs
- Clinical and model tuning parameters that must be prespecified for CRM designs
- Operating characteristics (expected DLTs, overdosing, correct MTD identification) evaluated via simulation
- Why simulating under multiple true dose-toxicity scenarios matters for design evaluation
- Worked example: a Phase I study of Olaparib + low-dose thoracic radiotherapy for extensive-stage small cell lung cancer
- The `crmsim()` function for simulating CRM trial designs (target, prior/true toxicity probabilities, cohort size, dose-toxicity model, etc.)
- Modified CRM designs (e.g. larger cohort sizes, skipping/jumping dose levels)
- Hands-on coding exercise