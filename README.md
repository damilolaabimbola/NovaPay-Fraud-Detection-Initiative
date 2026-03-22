# NovaPay Fraud Detection System

An end-to-end machine learning pipeline for detecting fraudulent 
financial transactions in real time.

## Overview
This project builds, trains, and evaluates four ML classifiers on 
50,000+ NovaPay transactions, achieving 100% precision with zero 
false positives on the test set.

## Key Results
| Model | Precision | Recall | F1 | ROC-AUC |
|---|---|---|---|---|
| **Random Forest** | **100%** | **92%** | **0.96** | **0.99** |
| XGBoost | 93% | 92% | 0.93 | 0.97 |
| LightGBM | 91% | 91% | 0.91 | 0.96 |
| Logistic Regression | 79% | 94% | 0.86 | 0.97 |

## Features
- Data cleaning & quality assessment
- 8 engineered risk features (velocity, account age, IP risk, etc.)
- SHAP explainability for every prediction
- Hyperparameter tuning with RandomizedSearchCV
- Production-ready saved model (`fraud_model_rf.joblib`)

## Tech Stack
Python · pandas · scikit-learn · XGBoost · LightGBM · SHAP · matplotlib

## Author
Damilola Abimbola
