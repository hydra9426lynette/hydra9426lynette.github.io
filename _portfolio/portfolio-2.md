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

A pediatric ICU produces blood-pressure readings by the thousand, most of them unremarkable. The question this
project asked was which ones weren't: which single low reading was noise, and which was the first sign a child
was getting worse. I built the R pipeline that cleaned, imputed, and reconciled that data — vitals, labs, ICD
codes, nursing flowsheets — into one dataset built to answer it.

Getting the threshold right meant applying AHA/PALS age-specific definitions of hypotension, correcting how age
itself was calculated, and separating a transient dip in one reading from a genuine patient-level decline. From
there, logistic and penalized regression, gradient boosting, and XGBoost competed to predict deterioration —
results I presented back to the clinical study team.
