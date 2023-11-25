# Heart Disease Prediction Project

![Heart.png](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRYAzmm_O-GdtiZ50AtQTaPPKnTjNM93zTbMA&usqp=CAU)

## Problem Statement

This project aims to predict heart disease based on various health-related features. The goal is to build a machine learning model that accurately predicts whether a person has heart disease or not, enabling early intervention and healthcare implications.

## Data Description

The dataset contains 303 patient records with 14 variables each, sourced from the UCI Machine Learning Repository. Key variables include age, sex, chest pain type, resting blood pressure, serum cholesterol, and more.

### Correlation Matrix

A correlation matrix visualizes the relationships between variables. It reveals insights into feature significance for heart disease prediction. For instance, chest pain type shows a positive correlation, while exercise-induced angina demonstrates a negative correlation with heart disease.

### Data Exploration Findings

- No missing values or duplicates were found.
- The dataset exhibits an imbalance in heart disease distribution.
- Outliers exist, particularly in cholesterol and blood pressure.
- Certain variables showcase correlation trends, like age and maximum heart rate.

## Machine Learning Model

**Logistic Regression** was chosen due to its suitability for binary classification problems, ability to handle various variable types, and ease of interpretation. The dataset was split into 80% training and 20% test sets using stratified sampling.

### Interpretation of Results

- **Model Accuracy**:
  - Training Data: 85.12%
  - Test Data: 81.97%

- **Confusion Matrix Metrics**:
  - Accuracy: 83.33%
  - Precision: 84.37%
  - Recall: 81.81%
  - F1 Score: 83.07%

### Receiver Operating Characteristic (ROC) Curve

The ROC curve illustrates the model's discrimination ability. An **Area Under Curve (AUC)** of 0.89 indicates favorable model performance.

## Conclusions

- The Logistic Regression model shows promise with an 82% accuracy rate on test data.
- Further enhancements could involve exploring different models, hyperparameter tuning, and feature engineering.

### Predictions

- **For Input (62,0,0,140,268,0,0,160,0,3.6,0,2,2):**
  - Predicted Result: 0 (No heart disease)
  - Actual Result: 0

- **For Input (55,0,1,132,342,0,1,166,0,1,2,2,0,2):**
  - Predicted Result: 1 (Heart disease)
  - Actual Result: 1

Thank you for exploring this heart disease prediction project!
