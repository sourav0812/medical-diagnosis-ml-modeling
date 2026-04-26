# Predictive Modeling for Medical Diagnosis

## Overview
An R-based machine learning and statistical modeling project that applies classification algorithms and neural networks to real-world medical datasets (breast cancer diagnosis and prostate cancer PSA prediction). The project evaluates multiple models, optimizes decision thresholds, and uses statistical validation techniques to select the best-performing model.

📊 Built as part of Harvard Extension School Data Science coursework

## Skills & Tools
- R (caret, neuralnet)
- Machine Learning Models (XGBoost, Random Forest, AdaBoost, CART, C5.0, Logistic Regression)
- Neural Networks (Softplus activation)
- AIC Stepwise Regression
- Hosmer–Lemeshow Goodness-of-Fit Test
- Classification Threshold Optimization (p = 0.5 vs p = 0.9)
- Model Evaluation (Accuracy, Sensitivity, Specificity, F1 Score)
- Data Preprocessing & Scaling (Min-Max Normalization)

## What This Project Does

**Classification Modeling** — Builds and compares 6 machine learning models to predict breast cancer malignancy, achieving 96.57% test accuracy using XGBoost

**Threshold Optimization** — Tests different probability cutoffs (p = 0.5 vs p = 0.9) to balance sensitivity and specificity, selecting the optimal model based on F1 score and out-of-sample performance

**Statistical Validation** — Uses AIC stepwise regression and Hosmer–Lemeshow testing to evaluate model fit and feature selection

**Neural Network Modeling** — Designs and trains multi-layer neural networks with Softplus activation to predict PSA levels, achieving 98% R² and 0.99 correlation

**Overfitting Analysis** — Compares training vs test performance across models to detect overfitting and improve generalization

## Key Concepts Demonstrated
- Classification vs Regression modeling
- Model comparison and selection
- Bias-variance tradeoff and overfitting detection
- Sensitivity vs specificity tradeoffs
- F1 score optimization
- Feature selection using statistical criteria (AIC)
- Neural network architecture and activation functions

## Datasets
- Breast Cancer Dataset — Used for classification (benign vs malignant)
- Prostate Cancer Dataset — Used for PSA prediction (regression)
