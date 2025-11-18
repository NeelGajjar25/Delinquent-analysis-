## Table of Contents
- <a href="#project-overview">Project Overview</a>
- <a href="#objectives">Objectives</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#eda-tasks-completed">EDA Tasks Completed</a>
- <a href="#key-insights-high-level">Key Insights (High-Level)</a>
- <a href="#technologies-used">Technologies Used</a>
- <a href="#file-included">File Included</a>
- <a href="#next-steps">Next Steps</a>
- <a href="#author">Author</a>


<h2><a class="file" id="project-overview"></a>Project Overview</h2>

This project focuses on analyzing customer financial behavior to identify individuals at high risk of becoming delinquent.
The Exploratory Data Analysis (EDA) phase uncovers patterns, correlations, and data quality issues to support future predictive modeling.

<h2><a class="file" id="objectives"></a>🎯Objectives</h2>

- Understand the dataset structure and key financial indicators
- Detect and treat missing values & anomalies
- Explore factors correlated with delinquency
- Prepare clean, imputed data for modeling
- Provide meaningful insights to guide risk prediction models

<h2><a class="file" id="project-structure"></a>📂 Project Structure</h2>

```
Delinquency Analysis
├── Data/
│   └── Delinquency_dataset.xlsx
├── Notebook/
│   └── Delinquency_analysis.ipynb
└── EDA_SummaryReport.docx
```
<h2><a class="file" id="eda-tasks-completed"></a>🧹 EDA Tasks Completed</h2>

- ✔ Dataset overview and variable types
- ✔ ML-based imputation for missing values
- ✔ Outlier detection in financial fields
- ✔ Correlation analysis for risk indicators
- ✔ Segmentation insights (employment & location patterns)

<h2><a class="file" id="key-insights-high-level"></a>🔍 Key Insights (High-Level)</h2>

- Lower Credit Score and higher Debt-to-Income Ratio show meaningful association with delinquency
- Outliers were found in Income and Loan Balance
- Certain locations and employment categories show higher delinquency density
- Imputation using Random Forest Regressor improved dataset quality and consistency


<h2><a class="file" id="technologies-used"></a>🛠 Technologies Used</h2>

- Python
- Pandas, NumPy
- Scikit-learn (ML-based imputation & analysis)
- Matplotlib / Seaborn (visualizations)
- Jupyter Notebooks


<h2><a class="file" id="next-steps"></a>🚧 Next Steps</h2>

- Feature engineering
- Predictive modeling (classification)
- Model validation and performance evaluation
- Bias, fairness, and ethical assessment
