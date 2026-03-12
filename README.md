# Heart-Disease-Prediction-using-Machine-Learning
Predicting heart disease risk using machine learning models with healthcare data from the UCI Heart Disease dataset.

Project Overview

This project focuses on predicting the risk of heart disease using machine learning techniques. By analyzing patient medical records, the model identifies patterns and risk factors associated with cardiovascular diseases.

The project demonstrates a complete data science workflow including data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

Dataset used: Heart Disease UCI Dataset

Project Objectives

Analyze medical data to identify patterns related to heart disease.

Normalize medical records for consistency.

Apply machine learning classification algorithms.

Evaluate model performance using multiple metrics.

Perform feature importance analysis to identify key health indicators.

Highlight ethical considerations in healthcare data usage.

Dataset Description

The dataset contains anonymized patient health records used for heart disease prediction.

Key features include:

Feature	Description
age	Age of the patient
sex	Gender of the patient
cp	Chest pain type
trestbps	Resting blood pressure
chol	Cholesterol level
thalach	Maximum heart rate achieved
exang	Exercise induced angina
oldpeak	ST depression induced by exercise
slope	Slope of peak exercise ST segment
ca	Number of major vessels colored by fluoroscopy
thal	Thalassemia condition

Target variable:

0 → No heart disease

1 → Presence of heart disease

Technologies Used

Python

Jupyter Notebook

Pandas

NumPy

Matplotlib

Seaborn

scikit-learn

Machine Learning Models Implemented

The following classification models were trained and evaluated:

Logistic Regression

Decision Tree

Random Forest

These models help predict whether a patient is likely to have heart disease based on medical attributes.

Model Evaluation Metrics

The models were evaluated using:

Accuracy Score

Confusion Matrix

Precision

Recall

F1 Score

ROC-AUC Score

The Random Forest model demonstrated strong predictive performance compared to the other models.

Feature Importance Analysis

Feature importance analysis was performed to identify the most influential factors contributing to heart disease prediction.

Important predictors include:

Age

Cholesterol levels

Maximum heart rate

Chest pain type

Blood pressure

Understanding these factors can help healthcare professionals assess cardiovascular risk more effectively.

Ethical Considerations

Healthcare data requires responsible handling and strict privacy protection.

Key ethical aspects include:

The dataset used is publicly available and anonymized.

No personally identifiable patient information is included.

Machine learning predictions should assist medical professionals rather than replace clinical decision-making.

Real-world healthcare AI systems must comply with regulations such as HIPAA and GDPR.

Project Workflow

Data Collection

Data Cleaning and Preprocessing

Exploratory Data Analysis (EDA)

Feature Scaling and Normalization

Model Training

Model Evaluation

Feature Importance Analysis

Results and Insights

The machine learning models successfully identified patterns within patient medical data that correlate with heart disease risk.

The Random Forest model achieved the best predictive performance and highlighted key medical indicators influencing cardiovascular health.

Future Improvements

Possible improvements include:

Hyperparameter tuning for better model performance

Using advanced models such as XGBoost

Building a web application for disease prediction

Integrating larger healthcare datasets
