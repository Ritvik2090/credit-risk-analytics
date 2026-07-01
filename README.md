# Credit Risk Analytics and Loan Approval Prediction

## Project Overview

This project analyzes a loan application dataset to identify the key factors influencing loan approval decisions and builds machine learning models to predict whether a loan application is likely to be approved.

The project follows a complete data analytics workflow, including data exploration, preprocessing, model building, evaluation, and business recommendations.

---

## Problem Statement

Financial institutions evaluate multiple applicant characteristics before approving a loan. The objective of this project is to:

- Analyze factors affecting loan approval.
- Identify the most influential applicant characteristics.
- Build predictive models for loan approval.
- Provide business insights that can support lending decisions.

---

## Dataset

**Dataset:** Loan Prediction Dataset

The dataset contains applicant information such as:

- Gender
- Marital Status
- Number of Dependents
- Education
- Self Employment Status
- Applicant Income
- Co-applicant Income
- Loan Amount
- Loan Term
- Credit History
- Property Area
- Loan Approval Status (Target Variable)

---

## Project Structure

```
credit-risk-analytics/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   ├── 01_data_understanding_and_eda.ipynb
│   ├── 02_data_preprocessing.ipynb
│   ├── 03_model_building.ipynb
│   └── 04_business_insights_and_recommendations.ipynb
│
├── reports/
│
├── images/
│
└── README.md
```

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## Workflow

### 1. Data Understanding and EDA

- Dataset exploration
- Missing value analysis
- Exploratory Data Analysis
- Business insights

### 2. Data Preprocessing

- Missing value treatment
- Feature encoding
- Feature scaling
- Data preparation

### 3. Model Building

Three machine learning models were developed:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

### 4. Model Evaluation

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Key Business Insights

- Applicants with a credit history had significantly higher loan approval rates.
- Graduate applicants showed higher approval rates than non-graduates.
- Married applicants received more approvals than unmarried applicants.
- Semi-urban applicants exhibited the highest approval rates.
- Applicant income alone was not a strong predictor of loan approval.
- Loan amount showed only a minor influence on approval decisions.

---

## Model Performance

| Model | Accuracy |
|--------|---------:|
| Logistic Regression | **78.9%** |
| Random Forest | 75.6% |
| Decision Tree | 70.7% |

Logistic Regression achieved the best overall performance while remaining highly interpretable, making it the preferred model for this project.

---

## Business Recommendations

Based on the analysis:

- Credit history should remain one of the primary indicators during loan evaluation.
- Additional verification can be considered for applicants with limited credit history.
- Income should not be used as the sole determinant for loan approval.
- Predictive models can assist loan officers by providing an initial assessment while supporting consistent decision-making.

---

## Future Improvements

Future enhancements may include:

- Hyperparameter tuning using GridSearchCV
- Testing advanced models such as XGBoost
- Addressing class imbalance
- Model explainability using SHAP
- Deployment using Streamlit

---

## Author

**Ritvik Jain**

If you found this project interesting, feel free to connect or provide feedback.
