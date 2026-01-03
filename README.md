Loan Approval Prediction with Explainability & Fairness
📌 Project Description

This project implements an end-to-end machine learning system to predict whether a loan application will be approved or rejected based on applicant features.
The solution goes beyond prediction accuracy by incorporating model explainability and a fairness quick-check, making it suitable for real-world financial decision support systems.

🎯 Problem Statement

Loan approval decisions depend on multiple financial and demographic factors. Manual evaluation can be slow and subjective.
This project aims to:

Predict loan approval outcomes automatically

Explain model decisions using interpretable AI techniques

Perform a basic fairness assessment on sensitive attributes

📊 Dataset

Dataset: Loan Approval Classification Dataset

Source: Kaggle

Type: Tabular (numerical + categorical features)

Key Features:

Applicant Income

Coapplicant Income

Loan Amount

Loan Term

Credit History

Gender, Education, Marital Status

Property Area

Target Variable:

Loan Approval Status (Approved / Rejected)

⚙️ Approach
1. Data Preprocessing

Cleaned and standardized column names

Handled missing values

Encoded categorical variables

Built a preprocessing pipeline for consistency

2. Model Training

Used supervised classification with scikit-learn

Combined preprocessing and model training using pipelines

Evaluated performance with standard classification metrics

3. Explainability (SHAP)

Applied SHAP (SHapley Additive exPlanations)

Identified the top 5 features influencing loan approval decisions

Improved transparency and interpretability of predictions

4. Fairness Quick-Check

Compared approval rates across selected sensitive attributes:

Gender

Education

Marital Status

Used approval rate differences to detect potential bias

Intended as a diagnostic check, not a full fairness audit

5. Deployment

Deployed the trained model using FastAPI

Exposed a REST endpoint (/score) for real-time predictions

✅ Project Outcomes

Trained loan approval prediction model

SHAP-based explainability (top decision drivers)

Fairness analysis on sensitive attributes

REST API for real-time loan scoring

🛠 Tech Stack

Python

scikit-learn

SHAP

FastAPI

Joblib

📈 Use Cases

Loan pre-screening automation

Explainable AI demonstration in fintech

Academic and college-level ML projects

Interview and portfolio project

📌 Conclusion

This project demonstrates a responsible machine learning workflow by combining predictive modeling with explainability and fairness considerations. It is suitable for academic submissions, interviews, and real-world financial analytics use cases.
