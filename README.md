# Household Debt Burden: Racialized Pathways and Wealth Disparities

This repository contains the code and documentation for an analysis of high household debt burden (Payment-to-Income Ratio > 40%) using data from the **2022 Survey of Consumer Finances (SCF)**. 

The analysis tests whether racial and wealth disparities in debt burden persist after controlling for socioeconomic characteristics, drawing on structural theories of financial vulnerability (e.g., Wherry's concept of "viral debt").

## 📄 Project Outputs

This repository contains two distinct written outputs derived from the same underlying analysis:

1. **Empirical Snapshot** (`HFWG 20260925 Emprical Snapshot.Rmd` / `.pdf`)  
   A concise, one-page summary of the core findings, methodology, and policy implications. This is formatted for quick reading, highlighting the divergence between raw debt burden rates and adjusted odds ratios across racial and wealth groups.

2. **Full Midterm Research Report** (`DATA 712 20260430 Roni Pitkowsky SCF.Rmd` / `.pdf`)  
   The comprehensive research report. This document contains the full theoretical background, detailed methodological approach (including complex survey design handling), extensive bivariate cross-tabulations, multivariate logistic regression results, and an in-depth discussion of limitations and future research directions.

## 📂 Repository Structure

```text
├── HFWG 20260925 Emprical Snapshot.Rmd   # One-page summary source code
├── DATA 712 20260430 Roni Pitkowsky SCF.Rmd # Full midterm report source code
├── manuscript/                           # LaTeX/RMarkdown template files for formatting
├── .gitignore                            # Excludes large data, cache, and draft files
└── README.md                             # This file
