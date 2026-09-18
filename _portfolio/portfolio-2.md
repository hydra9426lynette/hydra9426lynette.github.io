---
title: "Pediatric Hypotension Deterioration Modeling"
excerpt: "R pipeline for high-frequency pediatric EHR data, engineering AHA/PALS-based hypotension features and comparing ML models for deterioration prediction."
collection: portfolio
skills:
  - R
  - Logistic Regression
  - Penalized Regression
  - Gradient Boosting
  - XGBoost
---

* Built an end-to-end R pipeline turning raw EHR extracts (vitals, labs, ICD codes, nursing flowsheets) into a
  clean, encounter-level cohort ready for modeling
* Key finding: many single readings below standard low hypotension thresholds were transient noise, not linked
  to real patient-level deterioration — motivating a reading-level vs. patient-level distinction in the outcome
  definition
* Applied AHA/PALS age-specific hypotension thresholds and corrected continuous-age calculations feeding into
  those thresholds
* Compared logistic regression, penalized regression, gradient boosting, and XGBoost for deterioration
  prediction, evaluated with precision-recall curves (PRROC)
* R packages: dplyr, data.table, tidyr, lubridate, stringr for the pipeline; lme4 for mixed-effects modeling;
  gtsummary/gt and ggplot2 for reporting; PRROC for model evaluation
