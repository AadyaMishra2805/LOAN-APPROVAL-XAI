# Explainable Loan Approval Prediction using SHAP and LIME

## Project Overview

This project predicts whether a loan application will be approved using a Random Forest Classifier and provides transparent explanations using Explainable AI (XAI) techniques.

The goal is not only to make accurate predictions but also to understand why those predictions are made.

---

## Features

- Data preprocessing and cleaning
- Random Forest Classification
- Model evaluation
- Feature importance analysis
- SHAP explainability
- LIME explainability
- Visualization of influential features
- Model persistence using Joblib

---

## Dataset

Loan Prediction Dataset containing:

- Gender
- Married
- Dependents
- Education
- Self Employment Status
- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area

Target Variable:

- Loan Status (Approved / Rejected)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- SHAP
- LIME
- Matplotlib
- Joblib

---

## Model Performance

| Metric | Value |
|----------|----------|
| Accuracy | 75.61% |

---

## Key Findings

Top influential features:

1. Credit History
2. Applicant Income
3. Loan Amount
4. Coapplicant Income
5. Loan Amount Term

Least influential features:

- Gender
- Self Employed
- Education

---

## Explainable AI Techniques

### SHAP

Used for global and local model explainability.

Output:
- SHAP Summary Plot

### LIME

Used for individual prediction explanations.

Output:
- LIME Explanation HTML Report

---

## Project Structure

loan-approval-xai/

├── data/

├── models/

│ └── loan_model.pkl

├── reports/

│ ├── shap_summary.png

│ ├── feature_importance.png

│ ├── lime_explanation.html

│ └── report.pdf

├── notebooks/

│ └── Loan_Approval_XAI.ipynb

└── requirements.txt

---

## Conclusion

This project demonstrates how Explainable AI techniques can improve transparency and trust in machine learning-based loan approval systems. SHAP and LIME provide meaningful insights into model behavior while maintaining good predictive performance.
