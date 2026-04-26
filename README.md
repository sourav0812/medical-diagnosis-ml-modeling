# Predictive Modeling for Medical Diagnosis

This project applies statistical modeling and machine learning techniques to two real-world medical datasets:

- Breast Cancer Classification (Assignment 10)
- Prostate Cancer PSA Prediction (Assignment 12)

## Key Techniques
- Logistic Regression
- Random Forest, XGBoost, AdaBoost
- CART, C5.0
- Neural Networks (Softplus activation)
- AIC Stepwise Selection
- Hosmer-Lemeshow Test

## Highlights
- Achieved 96.57% test accuracy using XGBoost
- Optimized classification thresholds (p=0.5 vs p=0.9) to balance sensitivity and specificity
- Built neural networks achieving 98% R² and 0.99 correlation
- Identified overfitting through train vs test performance comparison

## Tools Used
- R (caret, neuralnet)
- Statistical modeling techniques
- Data preprocessing and scaling

## Files
- Assignment10.Rmd → Classification models
- Assignment12.Rmd → Neural networks & regression
