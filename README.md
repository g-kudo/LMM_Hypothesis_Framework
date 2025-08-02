# Linear Mixed Effects Model – Maternal Mental Health & Infant Sleep

This notebook explores how different aspects of maternal mental health might relate to infant sleep quality, using a **Linear Mixed Effects Model**. It works with repeated measurements over time and includes covariates to account for possible confounding factors.

## What This Notebook Does

- Reshapes the dataset into a **long format** so repeated measures can be modeled properly  
- Lets you define your own:
  - **Predictors** (e.g., prenatal depression, anxiety, sleep issues)
  - **Outcomes** (e.g., BISQ sleep quality scores)
  - **Covariates** (e.g., maternal age, socioeconomic status, gestational age at birth)
- Includes a handy built-in function to **check how complete the data is** across any group of columns—great for spotting where missing data might be a problem
- Fits a **mixed model** with a random intercept for each subject (to account for within-subject variation)
- Outputs a full summary of model coefficients and p-values so you can interpret the results easily

## Modularity and Reusability

The code is built to be **modular and flexible**.  
You can quickly swap in different predictors, outcomes, or covariates to test new hypotheses—no need to rewrite the whole thing. 

