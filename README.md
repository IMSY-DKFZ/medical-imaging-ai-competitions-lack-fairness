# Medical Imaging AI Competitions Lack Fairness  
_Reproducibility notebook for descriptive results_

## Overview

This repository contains a Python notebook `descriptive_analysis` that reproduces **all descriptive statistics and figures** reported in the paper: **Medical Imaging AI Competitions Lack Fairness**

The notebook documents the complete computational workflow underlying the *Results* section of the manuscript. It is intended to support transparency and reproducibility of the reported findings.

Importantly, this repository does **not** contain any model code, benchmarking pipelines, or training procedures. All analyses are strictly **descriptive** and based on aggregated screening results.

---

## Scope and purpose of the notebook

The notebook:

- reproduces **all numbers, percentages, and plots** reported in the manuscript,
- follows the **exact structure and ordering of the Results section** in the manuscript,
- documents each analysis step in a transparent and traceable manner.

The purpose of this notebook is **not** to introduce new analyses, but to make the reported results verifiable, auditable, and easy to follow for reviewers and readers.

No inferential statistics, hypothesis testing, or predictive modeling are performed.

---

## Data basis and usage restrictions

### Underlying data source

All analyses are based on a structured screening table resulting from a systematic review of medical imaging AI competitions. This table contains curated metadata extracted from competition websites, documentation, and associated publications.

### Access restrictions

The data underlying this study consist of manually curated screening results derived from publicly available challenge websites and publications. The compiled screening dataset cannot be shared publicly, as it contains challenge-level assessments that could enable the identification of individual challenges and organizers, even after anonymization, and may therefore expose specific entities to reputational or legal risks.

## Notebook structure

The notebook is organized to follow the results section of the manuscript, including the supplementary results. It is intentionally structured as a linear, step-by-step walkthrough of the reported results:

- **Data loading:**  The screening table is loaded at the start of the notebook. Subsequent sections operate on this in-memory representation.
- **Helper functions:**  Repeated operations are implemented as helper functions early in the notebook to keep the analysis consistent and to avoid duplicated code.
- **Results and supplementary results sections:**  Each subsequent notebook section corresponds to a results subsection in the paper and primarily presents the computed outputs (counts, percentages, and figures) that are reported in the manuscript.

