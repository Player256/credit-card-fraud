# Credit Card Fraud Detection

## Project Overview
The objective of this project is to detect fraudulent credit card transactions using machine learning techniques. Given the highly imbalanced nature of fraud data, various resampling methods were explored to improve the performance of the models.

## Techniques and Models
To handle the class imbalance, the following resampling techniques were employed:

- **SMOTE (Synthetic Minority Over-sampling Technique)**
- **ADASYN (Adaptive Synthetic Sampling)**
- **NearMiss (Undersampling technique)**
 
Several machine learning models were trained and evaluated:

- Logistic Regression
- XGBoost Classifier
- Random Forest Classifier
- Gradient Boosting Classifier
  
A custom pipeline was built to preprocess the data, apply the resampling techniques, and evaluate the models on various metrics.
