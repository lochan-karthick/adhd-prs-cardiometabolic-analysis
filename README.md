# ADHD Polygenic Risk and Cardiometabolic Traits in UK Biobank

This repository contains the Python Jupyter notebooks used for a study examining associations between genetic liability to attention-deficit/hyperactivity disorder (ADHD) and cardiometabolic traits in UK Biobank.

## Background

ADHD has been linked to poorer cardiometabolic health, but it is less clear whether genetic liability to ADHD is associated mainly with body mass index (BMI) or with a broader range of cardiometabolic traits. We investigated associations between an ADHD polygenic risk score (PRS-ADHD) and BMI, waist-to-hip ratio (WHR), systolic and diastolic blood pressure, carotid intima-media thickness (cIMT), and glycated haemoglobin (HbA1c). We also examined how these associations changed after adjustment for BMI.

## Notebooks

| Notebook | Analysis |
|---|---|
| `prs_adhd_std_vs_BMI.ipynb` | BMI, systolic blood pressure, and diastolic blood pressure analyses. |
| `prs_adhd_std_vs_WHR.ipynb` | Waist-to-hip ratio (WHR) analyses, including sex-related sensitivity analyses. |
| `PRS_ADHD_CIMT.ipynb` | Carotid intima-media thickness (cIMT) analyses and additional model checks. |
| `PRS_ADHD_Hb1ac.ipynb` | HbA1c analyses for participants without type 2 diabetes, along with a validation analysis including individuals with type 2 diabetes. |

Participants were grouped into low, medium, and high ADHD polygenic risk score (PRS-ADHD) tertiles to compare the distributions of cardiometabolic traits. Associations were then examined using ordinary least squares (OLS) regression, while generalised additive models (GAMs) were used to explore potential non-linear relationships.

## Manuscript

The associated manuscript is currently under review. A link will be added when it becomes publicly available. The manuscript provides the detailed methods, results, and interpretation.
