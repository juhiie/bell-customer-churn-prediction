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

---

## **Results & Insights**

- **Top churn drivers:** Income, competitor presence, building campaign lift  
- **High-risk segments:** Buildings/customers with >50% predicted churn probability  
- **Actionable recommendations:** Targeted retention campaigns for high-risk customers  
- **Potential revenue retention:** Estimated $X (calculated from dataset)

---

## **Repository Structure**

data/ → Raw and processed datasets
notebooks/ → Data cleaning, feature engineering, modeling, evaluation
src/ → Scripts for data processing and modeling
dashboards/ → Power BI dashboard & screenshots
requirements.txt
README.md


---

## **Getting Started**

1. Clone the repo:  
```bash
git clone https://github.com/juhiie/bell-customer-churn-prediction.git
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows
pip install -r requirements.txt
4. Run notebooks in order:
01_data_cleaning → 02_feature_engineering → 03_eda → 04_modeling → 05_evaluation_and_insights
