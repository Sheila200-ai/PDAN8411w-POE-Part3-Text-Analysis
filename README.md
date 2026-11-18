# PDAN 8411w POE: Pipelines and Text Data

**Name:** Sheila Shomang
**Institution:** Rosebank International
**Module:** PDAN 8411w, Programming for Data Analytics 1
**Date:** 2026/11/18

## About
Two text-analysis pipelines for a medical aid that wants to understand
negative customer reviews:
1. **Areas of concern:** topic modelling (TF-IDF + NMF)
2. **Customer sentiment:** a classifier built as a scikit-learn Pipeline
   (TF-IDF + chi-square feature selection + Logistic Regression)

## Files
- `PDAN8411w_ST10530465_Part3.ipynb`: full code with comments and outputs
- `PDAN8411w_ST10530465_Part3_POE_Report.pdf`: report to the client

## Data
Independent Medical Reviews (California Department of Managed Health Care),
downloaded from Kaggle. The CSV is not included because of its size.
To run the notebook, download `Independent_Medical_Reviews.csv` and place it
in the same folder as the notebook.

## Requirements
Python 3, pandas, numpy, scipy, scikit-learn, matplotlib, seaborn
