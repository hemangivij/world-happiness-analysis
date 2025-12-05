# world-happiness-analysis
Math 261A — Project 2: Multiple Regression Analysis Using World Happiness Report Data
# Happiness and Country-Level Determinants: A Regression Study

This repository contains the code and write-up for **Math 261A – Project 2**, which examines how economic, social, and institutional factors relate to national happiness using data from the **World Happiness Report (WHR 2025)**.

## Files

- `happiness_regression_project.Rmd` – Full analysis (data cleaning, EDA, regression model, diagnostics, discussion)
- `WHR2025.xlsx` – Dataset from the World Happiness Report
- `references.bib` – Bibliography entries used in the paper
- `apa.csl` – APA citation style file for formatting references
- `README.md` – Description of the project and repository structure

## Methods

The analysis uses:
- Multiple linear regression  
- Nonlinear effects (quadratic GDP term)  
- Interaction effects (GDP × Social Support)  
- Diagnostic plots for model validation  

The analysis was performed in **R** using the **tidyverse** suite of packages.

## Results Summary

Key findings include:
- Log GDP, social support, life expectancy, and freedom have strong positive associations with happiness.
- Corruption negatively affects happiness.
- There is evidence of diminishing returns to income.
- The interaction between GDP and social support suggests income matters more in supportive societies.

## Author
Hemangi Vij  
San Jose State University
