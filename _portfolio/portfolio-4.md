---
title: "PICUBE Pediatric Hypotension — Biostatistical Analysis Pipeline (R)"
excerpt: "SAP-driven R pipeline for a pediatric ICU hypotension study — AAP percentile thresholds, PALS hypotension flagging, and 24-hour deterioration outcomes."
collection: portfolio
skills:
  - R
  - SAP-Compliant Programming
  - Clinical Thresholds (AAP/PALS)
  - Data Validation
  - Cohort Derivation
---

Built and maintained the statistical analysis pipeline in R for PICUBE, a pediatric ICU study of blood-pressure
readings and clinical deterioration, implemented directly against a versioned Statistical Analysis Plan (SAP).

**Pipeline highlights:**
* Encounter-level derivations and cohort exclusions applied per SAP-specified criteria
* Height imputation via last-observation-carried-forward (LOCF), per SAP §2.3
* Parsing and validation of systolic/diastolic/mean arterial pressure (SBP/DBP/MAP) readings, including error-
  distribution checks to flag extreme discrepancies
* Age- and percentile-based hypotension thresholds using Flynn 2017 AAP percentiles
* PALS-based hypotension flagging (SAP §4.1) and a derived threshold pipeline (SAP §4.4) distinguishing transient
  reading-level hypotension from patient-level clinical outcomes
* Outcome labeling for death or CPR within 24 hours, feeding into the study's main analytic tables and figures
  (SAP §3.7)

This work sits alongside the machine-learning side of the same project (see the deterioration-modeling entry
below) but focuses specifically on the biostatistics/SAP-compliance layer: reproducible R code that turns a
written analysis plan into an auditable, versioned pipeline — no manual re-derivation between report versions.

**Skills:** R, SAP-compliant biostatistical programming, clinical thresholds (AAP/PALS), data validation, cohort
derivation, reproducible reporting

*No patient data, images, or real study output are shown here — this project involves protected pediatric
clinical data and is described at the methodology level only.*
