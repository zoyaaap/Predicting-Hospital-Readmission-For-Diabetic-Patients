# Predicting-Hospital-Readmission-For-Diabetic-Patients
# 📌Overview
This project aims to build a predictive model using real patient data to identify diabetic patients at risk of readmission. By flagging high-risk cases early, hospitals can take proactive measures to improve care and reduce costs. It focuses on helping healthcare providers identify which patients are likely to be readmitted within 30 days of discharge, so they can intervene early.

# 📚 Data
Source: UCI Machine Learning Repository\
Dataset: Diabetes 130-US hospitals for years 1999–2008
Size: 100,000+ patient records
Focus: Diabetic patient encounters from 130 US hospitals over 10 years

# 🛠️ Techniques Used
Data Cleaning: Handling missing values (?), converting categorical variables, removing invalid entries
Exploratory Data Analysis (EDA): Patient distribution, readmission patterns, length of stay
Feature Engineering: Encoding diagnosis columns, grouping discharge types, binarizing readmission outcome (≤30 days vs. others)
Modeling: XGBoost
Model Evaluation: Accuracy, Precision, Recall, F1 Score, ROC-AUC
Confusion Matrix & Classification Report

# 🔍 Key Insights
1. Number of prior inpatient visits was a strong predictor of readmission.
2. Discharge disposition heavily influenced readmission probability.
3. Patients prescribed more medications or with longer hospital stays were more likely to return.
