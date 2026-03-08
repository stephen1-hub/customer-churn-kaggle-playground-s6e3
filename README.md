# customer-churn-kaggle-playground-s6e3
# Kaggle Playground Series – Season 6 Episode 3
Customer Churn Prediction

## Overview
This project is based on the Kaggle Playground Series competition designed to help practitioners build machine learning skills through monthly challenges.

The objective was to predict the probability that a customer will churn.

## Dataset
Telco-style customer dataset containing demographic information, service usage, and billing details.

Target variable:
Churn (1 = customer left, 0 = customer stayed)

## Feature Engineering
Some engineered features include:
- Number of services used
- Tenure-based interaction features
- Correlation-based feature selection

## Models Tested
- XGBoost
- LightGBM
- Random Forest

## Model Evaluation
Evaluation metric: **ROC-AUC**

Best Validation Score:
**AUC ≈ 0.91**

### Interpretation
An AUC of 0.91 means that the model correctly ranks a randomly selected churned customer higher than a non-churned customer approximately **91% of the time**.

## Key Learnings
- Feature engineering had significant impact on performance
- Proper train/test feature alignment is critical
- Gradient boosting models performed best for this tabular dataset

## Future Improvements
- Cross-validation
- Hyperparameter tuning
- Model ensembling
