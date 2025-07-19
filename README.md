# Predicting-Hospital-Readmission-For-Diabetic-Patients
# 📌Overview
This project aims to build a predictive model using real patient data to identify diabetic patients at risk of readmission. By flagging high-risk cases early, hospitals can take proactive measures to improve care and reduce costs. It focuses on helping healthcare providers identify which patients are likely to be readmitted within 30 days of discharge, so they can intervene early.

# 📚 Data
Source: UCI Machine Learning Repository\
Dataset: Diabetes 130-US hospitals for years 1999–2008\
Size: 100,000+ patient records\
Focus: Diabetic patient encounters from 130 US hospitals over 10 years\

# 🛠️ Techniques Used
Data Cleaning: Handling missing values (?), converting categorical variables, removing invalid entries\
Exploratory Data Analysis (EDA): Patient distribution, readmission patterns, length of stay
Feature Engineering: Encoding diagnosis columns, grouping discharge types, binarizing readmission outcome (≤30 days vs. others)\
Modeling: XGBoost\
Model Evaluation: Accuracy, Precision, Recall, F1 Score, ROC-AUC\

# 🤖 Model Performance and Evaluation
The final model achieved an impressive 94% overall accuracy on the test set, with a ROC AUC score of 0.9586, indicating excellent ability to distinguish between readmitted and non-readmitted patients. The classification report showed a precision of 0.99 and a recall of 0.88 for the positive class (readmitted), resulting in a strong F1-score of 0.93. This means the model is highly reliable in predicting readmissions, accurately identifying 88% of true readmission cases while maintaining a low false positive rate. The model also performed well on the negative class, ensuring balanced performance across both outcomes. These metrics suggest the model is suitable for real-world clinical use, where early identification of at-risk patients can help reduce costs and improve patient care outcomes.

# 🔍 Key Insights
1. Number of prior inpatient visits was a strong predictor of readmission.
2. Discharge disposition heavily influenced readmission probability.
3. Patients prescribed more medications or with longer hospital stays were more likely to return.
