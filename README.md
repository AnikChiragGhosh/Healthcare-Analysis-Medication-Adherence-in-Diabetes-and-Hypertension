# Healthcare-Analysis-Medication-Adherence-in-Diabetes-and-Hypertension
This project focuses on analyzing medication adherence among patients diagnosed with Diabetes and Hypertension using a real-world dataset. The goal is to understand the key drivers of adherence behavior and build predictive models to identify high-risk non-adherent patients.

## 🧠 Objectives

• Explore and clean patient-level healthcare data.
• Engineer new features such as refill gaps, polypharmacy flags, and complication development.
• Build and evaluate predictive models (Logistic Regression and Random Forest) to classify patients as Adherent or Non-Adherent.
• Identify key factors impacting medication adherence.
• Provide actionable recommendations for pharmaceutical companies and healthcare policymakers.


## 🛠️ Dataset Summary

Dataset Source: Mendeley Data — Diabetes and Hypertension Medication Adherence Dataset
### Key Features:
Demographics: Age, Gender
Clinical: Diagnosis, Complications, Comorbidities
Financial: Annual Claim Amount, Annual Contribution
Medication Metrics: Units Total, Refill Patterns

## 📈 Key Analytical Steps
### Exploratory Data Analysis (EDA):
• Distribution of adherence behavior across demographics and clinical variables.
• Correlation analysis to uncover relationships among variables.
### Feature Engineering:
• Creation of POLYPHARMACY_FLAG, REFILL_GAP, COMPLICATION_COUNT.
• Binning of age into AGE_GROUP.
### Model Building:
• Logistic Regression and Random Forest Classifier.
• Hyperparameter tuning (max depth, number of trees, entropy criterion).
• Evaluation Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.
### Feature Importance Analysis:
• UNITSTOTAL and ANNUALCLAIMAMOUNT emerged as top predictors.
• Clinical variables like AGE, COMPLICATIONDEVELOPMENT, and COMORBIDITY showed moderate influence.

## 🎯 Results
Random Forest achieved strong classification performance with feature-driven insights.
Top predictors of non-adherence:
High Units Total (Medication Burden)
High Annual Claim Amount (Healthcare Burden)
Advanced Age
Presence of Complications and Comorbidities

                                  Model	Accuracy	                      ROC-AUC
    Logistic Regression	     (0.5722391364517022)	               (0.5529549042542312)
    Random Forest	         (0.808746194298367)	               (0.8935628866901877)









