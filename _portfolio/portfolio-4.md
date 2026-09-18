---
title: "PICUBE Pediatric Hypotension — Biostatistical & ML Analysis Pipeline (R)"
excerpt: "SAP-driven R pipeline for a pediatric ICU hypotension study — AAP percentile thresholds, PALS hypotension flagging, and ML deterioration modeling."
collection: portfolio
skills:
  - R
  - SAP-Compliant Programming
  - Clinical Thresholds (AAP/PALS)
  - Data Validation
  - Logistic Regression
  - Gradient Boosting
  - XGBoost
---

* Built an R pipeline for PICUBE, a pediatric ICU study of blood pressure and clinical deterioration, mirroring
  the written Statistical Analysis Plan (SAP) section by section so nothing was re-derived by hand between
  report versions
* Encoded the SAP's cohort exclusion criteria and height-imputation rules directly into code; validated
  blood-pressure readings against Flynn's 2017 AAP percentiles
* Built PALS-based hypotension flagging logic distinguishing a single noisy reading from a real patient-level
  decline
* Key finding: many single readings below standard low hypotension thresholds were transient noise, not linked
  to real patient-level deterioration — motivating a reading-level vs. patient-level distinction in the outcome
  definition
* Compared logistic regression, penalized regression, gradient boosting, and XGBoost for deterioration
  prediction, evaluated with precision-recall curves (PRROC)
* R packages: dplyr, data.table, tidyr, lubridate, stringr for the pipeline; lme4 for mixed-effects modeling;
  gtsummary/gt and ggplot2 for reporting; PRROC for model evaluation
* Supervised by [Dr. Andrew Geneslaw, MD, MS](https://www.pediatrics.columbia.edu/profile/andrew-s-geneslaw-md),
  Pediatric Critical Care Medicine, Columbia University Irving Medical Center / Morgan Stanley Children's
  Hospital

*No patient data or real study output appears here; this project involves protected pediatric clinical data and
is described at the methodology level only.*
