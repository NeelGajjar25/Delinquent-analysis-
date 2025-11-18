## 📚 Table of Contents
- [Project Overview](#-project-overview)
- [Objectives](#-objectives)
- [Repository Structure](#-repository-structure)
- [EDA Tasks Completed](#-eda-tasks-completed)
- [Key Insights](#-key-insights-high-level)
- [Technologies Used](#-technologies-used)
- [File Included](#-file-included)
- [Next Steps](#-next-steps)
- [Author](#-author)


Project Overview

This project focuses on analyzing customer financial behavior to identify individuals at high risk of becoming delinquent.
The Exploratory Data Analysis (EDA) phase uncovers patterns, correlations, and data quality issues to support future predictive modeling.

🎯 Objectives

Understand the dataset structure and key financial indicators
Detect and treat missing values & anomalies
Explore factors correlated with delinquency
Prepare clean, imputed data for modeling
Provide meaningful insights to guide risk prediction models

📂 Repository Structure

📂 root
│── Data/
│   ├── Delinquency_dataset.xlsx
│ 
│── Notebook/
│   └── Delinquency_analysis.ipynb
│ 
│── EDA_SummaryReport.docx


🧹 EDA Tasks Completed

✔ Dataset overview and variable types
✔ ML-based imputation for missing values
✔ Outlier detection in financial fields
✔ Correlation analysis for risk indicators
✔ Segmentation insights (employment & location patterns)

🔍 Key Insights (High-Level)

Lower Credit Score and higher Debt-to-Income Ratio show meaningful association with delinquency
Outliers were found in Income and Loan Balance
Certain locations and employment categories show higher delinquency density
Imputation using Random Forest Regressor improved dataset quality and consistency


🛠 Technologies Used

Python
Pandas, NumPy
Scikit-learn (ML-based imputation & analysis)
Matplotlib / Seaborn (visualizations)
Jupyter Notebooks


🚧 Next Steps

Feature engineering
Predictive modeling (classification)
Model validation and performance evaluation
Bias, fairness, and ethical assessment
