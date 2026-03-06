# BRFSS 2022 — Smoking Status & Mental Health (Group Project)

## What this project does
Analyzes the association between **smoking status** and **mentally unhealthy days** using **BRFSS 2022** (U.S. adult survey).

## My contribution
This was a group project. I led the **multivariable modeling and the subsequent diagnostics/interpretation**, including:
- confounder adjustment and model comparison
- weighted analysis (BRFSS survey weight variable used in the report)
- robust inference / diagnostics (e.g., QQ, heteroskedasticity checks, VIF, influence)

## Data
- Source: **BRFSS 2022** (Behavioral Risk Factor Surveillance System).
- Data files are **not included** in this repository. See `data/README.md` for download notes.

## Methods (high-level)
- Outcome: mentally unhealthy days (transformed as needed)
- Exposure: smoking status categories
- Covariates: demographic + lifestyle factors
- Models: multivariable regression with diagnostics and robustness checks

## Report
- Live HTML report (GitHub Pages): (to be added)

## Reproducibility (summary)
Open `Report.rmd` and knit the report after placing the BRFSS 2022 data under `data/` (see `data/README.md`).