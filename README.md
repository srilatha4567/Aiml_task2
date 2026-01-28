# AI & ML Internship - Task 2: Data Cleaning & Missing Value Handling

## Overview
This task involved identifying and resolving data quality issues, specifically focusing on missing value imputation and dataset validation to prepare data for Machine Learning.

## Cleaning Steps Performed
* **Missing Data Audit:** Identified null values using `.isnull().sum()`.
* **Pattern Visualization:** Generated bar charts to visualize the density of missing information across features.
* **Numerical Imputation:** Applied **Median Imputation** to fill numerical gaps, ensuring the model remains robust against outliers.
* **Categorical Imputation:** Used **Mode Imputation** (most frequent value) for string-based/categorical columns.
* **Feature Pruning:** Dropped columns with extremely high missing percentages (>40%) to reduce noise.
* **Validation:** Verified the final dataset size and confirmed zero remaining null values.

## Key Findings
- **Data Quality:** Initially, several features were unfit for modeling due to sparsity.
- **Before vs. After:** Maintained dataset integrity while ensuring every row is complete for algorithm compatibility.

## Tools Used
* **Python Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Google Colab / Jupyter Notebook
