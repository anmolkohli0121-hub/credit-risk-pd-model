# credit-risk-pd-model
End-to-end probability of default model using German credit data
Credit Risk PD Model (Germany Dataset)

🔹 Business Context
Banks such as Deutsche Bank and HSBC use probability of default (PD) models to:
Assess borrower risk
Price loans
Meet regulatory requirements
Optimize capital under Basel frameworks

This project simulates a real-world credit risk workflow.

🔹 Objective
Build an end-to-end machine learning model to predict borrower default and support credit decision-making.

🔹 Dataset
German credit dataset containing borrower demographics, financial behavior, and loan characteristics.

🔹 Project Workflow
✔ Data cleaning and preprocessing
Handling missing values
Encoding categorical variables
Feature scaling and transformations

✔ Exploratory data analysis
Risk segmentation by age, income, and loan type
Identification of high-risk borrower profiles

✔ Feature engineering
Age bucketing
Risk proxies
Behavioral indicators

✔ Model development
Logistic regression baseline
Model interpretability
Performance validation

✔ Model evaluation
ROC AUC
KS statistic
Precision recall tradeoff
Risk cutoff selection

✔ Ongoing work
Scorecard development
Dashboard for credit monitoring
Explainability (SHAP)
Business decision framework

🔹 Results (current)
ROC AUC: 0.80
KS: 0.50

🔹 Tools
Python | Pandas | Scikit-learn | SQL | Power BI | Excel

🔹 Future Scope
Basel-compliant PD scorecard
Portfolio risk segmentation

Note - Raw dataset not uploaded due to data privacy and governance considerations.
Automated credit decision support

Deployment via Streamlit dashboard
