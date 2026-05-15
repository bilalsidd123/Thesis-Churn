# Customer Churn Prediction Project

## Objective
To predict customer churn using machine learning and identify key factors influencing customer attrition.

## Dataset
Telco Customer Churn Dataset (Kaggle)

## Structure
- data/
  - raw
  - processed
- notebooks/
  - 01_eda
  - 02_preprocessing
  - 03_model_comparison
  - 04_interpretation_SHAP
- outputs/

## Models Used
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

## Key Findings
- Tenure, monthly charges, and total charges are main churn drivers
- Logistic Regression performed best along with a threshold of 0.4.

## Class Imbalance
The Telco Customer Churn dataset is slightly imbalanced because the number of customers who did not churn is higher than the number of customers who churned. For this reason, greater importance was given to Recall, F1-score, and ROC-AUC during model evaluation.

## Tools
Python, Scikit-learn, SHAP
