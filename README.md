# CreditWise Loan System

A machine learning-based loan approval prediction system that helps financial institutions make faster and more reliable lending decisions. The model predicts whether a loan application should be approved or rejected using applicant financial and demographic information.

## Features
- Data cleaning and preprocessing
- Missing value handling
- Categorical feature encoding
- Feature engineering and scaling
- Loan approval prediction using machine learning
- Model comparison and evaluation

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Models Used
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes

## Key Highlights
- Applied log transformation to reduce feature skewness.
- Engineered additional features using Credit Score and DTI Ratio.
- Performed feature scaling using StandardScaler.
- Tuned KNN using GridSearchCV.
- Achieved **87.0% accuracy** with Logistic Regression.

## Results
Logistic Regression delivered the best overall performance with **87.0% accuracy** and **79.0% F1-score**. Credit Score and Debt-to-Income (DTI) Ratio were identified as the most important factors influencing loan approval decisions.

Depending on business requirements, **Gaussian Naive Bayes can also be considered for deployment** due to its higher precision, making it suitable for scenarios where minimizing risky loan approvals is a priority.

## Future Improvements
- Deploy the model using Flask/FastAPI
- Build a web-based prediction interface
- Experiment with ensemble models such as Random Forest and XGBoost
- Add model explainability using SHAP
