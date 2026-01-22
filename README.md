# Tox21 Toxicity Prediction

## Overview
This project explores the development, evaluation, and interpretation of machine learning models
for predicting chemical toxicity using the Tox21 dataset.

The goal is to assess how molecular fingerprints and classical ML models can be used
to support toxicity screening in early-stage drug discovery.

## Dataset
- **Source:** Tox21 Challenge Dataset
- **Description:** Contains chemical compounds labeled across multiple toxicity targets
- **Challenge:** Highly imbalanced classes and sparse molecular representations

## Methods
- Data cleaning and preprocessing
- Molecular fingerprint generation
- Exploratory data analysis (EDA)
- Model training and evaluation:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting / XGBoost
- Model interpretation using SHAP

## Results
Models were evaluated using metrics appropriate for imbalanced data, including ROC-AUC
and confusion matrices. Feature importance analysis highlights key molecular substructures
associated with toxicity signals.

## Tools & Libraries
- Python
- pandas, numpy
- scikit-learn
- XGBoost
- RDKit
- SHAP

## Project Structure
