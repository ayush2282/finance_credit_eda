📊 Credit Card Customer Behavior & Risk Analysis (EDA)
🔹 Project Overview

This project performs an exploratory data analysis (EDA) on a banking credit card dataset to understand customer spending, repayment behavior, and default risk. The analysis focuses on behavioral patterns and risk indicators prior to any machine learning modeling.

🔹 Objectives

Understand credit limit distribution

Analyze customer demographics

Study repayment behavior over time

Compare default vs non-default customers

Identify key risk signals using visualization

🔹 Dataset

Public credit card dataset (banking domain)

Customer demographics

Credit limits

Monthly billing & payment history

Repayment status

Default indicator

🔹 Tools & Technologies

Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook
(SQL integration planned for validation in future iterations)

🔹 Project Structure
finance-credit-eda/
│
├── data/
│   └── raw/
├── notebooks/
│   ├── 01_data_loading.ipynb
│   └── 03_eda_visualization.ipynb
├── sql/
│   └── analysis_queries.sql
└── README.md
🔹 Key Findings

Credit limits and financial behavior are highly skewed

Repayment delays are strongly linked to default risk

Credit limit alone does not guarantee low risk

Consistent spending and payment patterns exist across months

🔹 Conclusion

This EDA highlights repayment behavior as the strongest risk indicator in credit card customers. The insights can support risk monitoring, policy decisions, and future predictive modeling.
