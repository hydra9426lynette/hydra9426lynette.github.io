---
title: "High-Dimensional Genetic Inference"
excerpt: "R-based simulations and Approximate Bayesian Computation for parameter inference in high-dimensional single-cell DNA-sequencing data."
collection: portfolio
skills:
  - R
  - Single-Cell DNA Sequencing
  - Approximate Bayesian Computation
  - Random Forests
  - Sequential Monte Carlo
  - Bayesian Statistics
---

Some likelihoods are too complicated to write down, let alone maximize — which is the usual excuse for reaching
for Approximate Bayesian Computation. I used it here, paired with random forests and sequential Monte Carlo, to
infer parameters from high-dimensional single-cell DNA-sequencing data where the mechanism was too tangled for a closed-form
model.

Before any of that, there was the less elegant work in R: quality-control on the sequencing reads, and simulations
built to test whether the statistical methods themselves could be trusted to recover the right answer from noisy,
high-dimensional genetic data.
