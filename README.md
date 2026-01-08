# Bell Customer Churn Prediction

Predictive modeling project for Bell Canada to identify high-risk customers and support targeted retention strategies.

---

## **Project Overview**

Bell Canada wants to reduce customer churn in its TV subscription service and improve campaign ROI.  
The dataset includes building-level subscriber and campaign data from 2016–2018.  
**Objective:** Predict post-campaign churn and identify actionable segments.

---

## **Key Features & Techniques**

- Data cleaning & preprocessing (handling missing values, encoding features)  
- Feature engineering (revenue per customer, building penetration, competitor influence)  
- Exploratory Data Analysis (EDA)  
- Machine Learning models: Logistic Regression, Random Forest, XGBoost  
- Model evaluation: ROC-AUC, F1-score, precision, recall  
- Explainability: SHAP / feature importance  
- Business insights: high-risk segments, predicted churn probabilities, ROI recommendations


python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
pip install -r requirements.txt
4. Run notebooks in order:
01_data_cleaning → 02_feature_engineering → 03_eda → 04_modeling → 05_evaluation_and_insights
