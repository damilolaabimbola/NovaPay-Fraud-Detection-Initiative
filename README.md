# NovaPay Fraud Detection System
A production-ready, explainable machine learning system for detecting fraudulent transactions across NovaPay's payment network.

## Overview
This project delivers an end-to-end fraud detection pipeline built 
on 50,000+ real transactions — from raw data cleaning through to a 
deployed, explainable ML model achieving **100% precision** with 
zero false positives.

## Key Results
| Model | Precision | Recall | F1 | ROC-AUC |
|---|---|---|---|---|
| **Random Forest** | **100%** | **92%** | **0.96** | **0.99** |
| XGBoost | 93% | 92% | 0.93 | 0.97 |
| LightGBM | 91% | 91% | 0.91 | 0.96 |
| Logistic Regression | 79% | 94% | 0.86 | 0.97 |

## Key Findings
- New accounts (<90 days) have **36–46% fraud rate** vs 1–2% mature
- High-velocity transactions (≥3/hr) show **70–85% fraud rate**
- Velocity-based features deliver an **8.42× detection lift**
- Night hours (0–5 AM) carry **1.92× higher fraud probability**

## Features
- Data cleaning & quality assessment
- 8 engineered risk features (velocity, account age, IP risk, etc.)
- SHAP explainability for every prediction
- Hyperparameter tuning with RandomizedSearchCV
- Production-ready saved model (`fraud_model_rf.joblib`)

## Tech Stack
Python · pandas · scikit-learn · XGBoost · LightGBM · SHAP · matplotlib
