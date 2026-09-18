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

Every clinical study has a written plan and, eventually, a gap between what the plan says and what the code
actually does. My job on PICUBE — a pediatric ICU study of blood pressure and clinical deterioration, under
[Dr. Andrew Geneslaw, MD, MS](https://www.pediatrics.columbia.edu/profile/andrew-s-geneslaw-md) of Columbia's
Pediatric Critical Care Medicine division — was to close that gap: an R pipeline built to mirror the Statistical
Analysis Plan section by section, so nothing was re-derived by hand between report versions.

That meant encoding the plan's cohort exclusions and height-imputation rules directly, validating blood-pressure
readings against Flynn's 2017 AAP percentiles, and building the PALS-based hypotension logic that tells a single
noisy reading apart from a real patient-level decline — the same distinction the deterioration-modeling work
below relies on, seen here from the compliance side rather than the modeling side.

*No patient data or real study output appears here; this project involves protected pediatric clinical data and
is described at the methodology level only.*
