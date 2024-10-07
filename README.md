# Costumer_Churn_Prediction

Customer Churn Prediction
This repository provides a project for predicting customer churn using machine learning. The objective is to help businesses identify customers at risk of leaving, enabling proactive retention strategies.

Contents
Overview
Project Structure
Data Processing
Modeling & Evaluation
Model Tuning & Interpretation
Installation & Usage
References
Overview
Customer churn prediction helps businesses retain customers by identifying those likely to leave. This project preprocesses customer data, analyzes features, and applies machine learning models to predict churn.

Project Structure
data/: Original and processed datasets.
notebooks/: Jupyter notebooks for data processing, EDA, and modeling.
models/ & tuned_models/: Pre-trained models and tuned versions.
machine_learning.pdf: Detailed project report.
Data Processing
The dataset contains customer information like monthly charges and tenure. Processing steps:

Cleaning & Missing Values: Handle missing data and encode categorical features.
Feature Engineering: Create additional features (e.g., CLV, TotalServices).
Scaling & Outliers: Normalize features and manage outliers for optimal modeling.
Modeling & Evaluation
Various machine learning models (Logistic Regression, Decision Tree, Random Forest, Gradient Boosting) are trained and evaluated. Random Forest achieves the best accuracy and ROC-AUC scores.

Model Tuning & Interpretation
Hyperparameter tuning (GridSearchCV) optimizes model performance. Feature importance and LIME are used for interpreting model decisions, with MonthlyCharges and Tenure being key predictors.

Installation & Usage
Install Dependencies:

pip install -r requirements.txt
Run Notebooks: Explore data and train models using ml_churn.ipynb.
Inference: Use pre-trained models for predictions.
References
Scikit-learn Documentation
Python
Pandas
Matplotlib
For more details, refer to machine_learning.pdf.
