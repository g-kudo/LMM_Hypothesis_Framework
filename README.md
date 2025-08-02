# Linear Mixed Effects Model – Maternal Mental Health & Infant Sleep

This notebook investigates how maternal mental health may influence infant sleep quality using a **Linear Mixed Effects Model**. The analysis focuses on repeated measurements across time and includes covariates to account for potential confounds.

## What This Notebook Does

- Prepares the dataset in **long format** to support repeated-measures modeling  
- Defines and accepts user-specified variables:
  - **Predictors** 
  - **Outcomes** 
  - **Covariates** 
- Includes a built-in utility to **check the proportion of complete cases** across specified columns, helping to identify bottlenecks due to missing data
- Fits a **linear mixed model** with a random intercept for each subject
- Outputs a **detailed summary** of model coefficients and p-values

## Modularity and Reusability

The code is designed to be **modular** and **adaptable**.  
Key inputs such as predictors, outcomes, and covariates can be easily adjusted to test alternative hypotheses with minimal code changes.
