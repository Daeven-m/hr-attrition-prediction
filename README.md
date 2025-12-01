HR Attrition Prediction Project

This project analyzes HR data to understand why employees leave a company and builds a logistic regression model to identify employees most at risk of attrition. The goal is to help HR make decisions supported by data, reduce turnover, and improve employee satisfaction.

Project Overview

The dataset includes 15,000 synthetic employee records modeled after the Google Advanced Data Analytics capstone. Features include satisfaction, evaluation scores, workload, tenure, salary levels, accidents, and promotions.

This project follows a complete analytics workflow:

Data cleaning and preparation

Exploratory data analysis (EDA)

Visualization of key trends and drivers

Logistic regression modeling

Model evaluation

Business recommendations for HR

Key Findings

The analysis revealed several clear patterns:

Employees with low satisfaction leave at a much higher rate

High monthly hours correlate with burnout and increased turnover

Employees without promotions in the last five years leave more often

Lower salary groups experience significantly higher attrition

Mid-tenure employees are more prone to quitting than new hires

These insights are consistent across visual and statistical analyses.

Modeling Approach

A logistic regression model was used to predict whether an employee would leave.

Performance:

Strong ROC-AUC

Solid accuracy

Good balance of precision and recall

Logistic regression was chosen for interpretability, making it easy for HR to understand the reasons behind each prediction.

Tools Used

Python

Pandas

NumPy

Seaborn / Matplotlib

Scikit-Learn

Jupyter Notebook

Repository Structure
hr-attrition-prediction/
│
├── README.md
├── notebook/
│   └── HR_Attrition_Analysis.ipynb
├── data/
│   └── HR_capstone_dataset.csv
├── visuals/
│   └── *.png
├── reports/
│   └── HR_Attrition_Executive_Summary.pdf
└── models/

Business Value

This project provides HR teams with a simple and effective framework for:

Identifying employees at risk of leaving

Understanding root causes of attrition

Prioritizing workload, compensation, and promotion improvements

Reducing turnover-related costs

The model and visuals support data-informed decision-making at every level.

Author

Daeven Morgan
Data & Operations Analyst
SQL • Python • Power BI • Excel • Automation
LinkedIn: https://www.linkedin.com/in/daeven-morgan-4664741a4
