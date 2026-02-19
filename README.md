# Credit Risk Probability of Default (PD) Model  
### German Credit Dataset
## Key Highlights
- End-to-end Probability of Default (PD) modeling pipeline  
- Realistic banking use case aligned with Basel frameworks  
- Strong model performance (ROC AUC: 0.80, KS: 0.50)  
- Interpretable logistic regression baseline  
- Business-oriented credit risk insights
  
## Business Context
Financial institutions use Probability of Default (PD) models to assess borrower risk, price loans, meet regulatory requirements, and optimize capital under Basel frameworks.

Banks such as Deutsche Bank and HSBC rely on similar models to support credit decision-making.

This project simulates a real-world credit risk modeling workflow.

---

## Objective
Develop an end-to-end machine learning model to predict borrower default risk and support lending decisions.

---

## Dataset
German Credit dataset containing borrower demographics, financial behavior, and loan characteristics.

---

## Project Workflow

### Data Preparation
- Data cleaning and preprocessing  
- Handling missing values  
- Encoding categorical variables  
- Feature scaling and transformations  

### Exploratory Data Analysis
- Risk segmentation by age, income, and loan type  
- Identification of high-risk borrower profiles  

### Feature Engineering
- Age bucketing  
- Risk proxies  
- Behavioral indicators  

### Model Development
- Logistic regression baseline  
- Model interpretability  
- Performance validation  

### Model Evaluation
- ROC AUC  
- KS statistic  
- Precision–recall tradeoff  
- Risk cutoff selection  

---

## Current Results
- ROC AUC: **0.80**  
- KS Statistic: **0.50**

---

## Tools & Technologies
Python • Pandas • Scikit-learn • SQL • Power BI • Excel

---

## Ongoing Work
- Scorecard development  
- Dashboard for credit monitoring  
- Model explainability (SHAP)  
- Business decision framework  

---

## Future Scope
- Basel-compliant PD scorecard  
- Portfolio risk segmentation  
- Automated credit decision support  
- Deployment via Streamlit dashboard

  ## How to Run This Project

1. Clone the repository:
   git clone https://github.com/anmolkohli0121-hub/credit-risk-pd-model.git

2. Navigate to the project folder:
   cd credit-risk-pd-model

3. Create and activate a virtual environment (recommended)

4. Install required packages:
   pip install -r requirements.txt

5. Open Jupyter Notebook:
   jupyter notebook

6. Run the notebooks inside the `notebooks/` folder

---

## Note on Data
The raw dataset is not included due to data governance considerations.

---

## Author
Anmol Kohli — Credit Risk & Analytics Enthusiast
