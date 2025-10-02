# Stroke Risk Prediction using Machine Learning

## Project Overview
This project implements multiple machine learning models to predict stroke risk based on patient health data for MSc Artificial Intelligence.

## Dataset
- **Source**: Healthcare stroke prediction dataset
- **Records**: 5,110 patients
- **Features**: 12 clinical and demographic attributes
- **Target**: Stroke occurrence (binary classification)

## Models Implemented
- Logistic Regression
- Random Forest  
- Support Vector Machine
- K-Nearest Neighbors
- XGBoost

## Key Findings
- Logistic Regression achieved best performance (AUC: 0.786)
- Age identified as strongest predictor (32.4% importance)
- Successful handling of class imbalance using SMOTE
- 42% recall rate for stroke detection

## Installation & Requirements
```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn
