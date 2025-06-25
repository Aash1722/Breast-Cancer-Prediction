# Breast-Cancer-Prediction
Logistic and Lasso regression models to predict breast cancer diagnosis (malignant or benign) using the Wisconsin Diagnostic dataset.

## 📌 Project Overview

This project uses the Wisconsin Diagnostic Breast Cancer dataset to predict whether a tumor is malignant or benign using logistic and lasso regression models. The goal is to evaluate model performance and choose the best approach for accurate classification.

## 📊 Dataset Information

The dataset contains 569 observations and 11 variables (10 features + 1 target).  
Source: UCI ML Repository - [Wisconsin Diagnostic Breast Cancer (WDBC) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic))

### Dictionary

| Variable | Role | Description |
|----------|------|-------------|
| `id` | ID | Patient identifier |
| `diagnosis` | Target | M = malignant, B = benign |
| `radius_mean` | Feature | Mean distance from center to perimeter points |
| `texture_mean` | Feature | Standard deviation of gray-scale values |
| `perimeter_mean` | Feature | Perimeter of tumor |
| `area_mean` | Feature | Area of tumor |
| `smoothness_mean` | Feature | Variation in radius lengths |
| `compactness_mean` | Feature | (Perimeter² / Area) - 1 |
| `concavity_mean` | Feature | Severity of concave portions |
| `concave_points_mean` | Feature | Number of concave sections |
| `symmetry_mean` | Feature | Symmetry of tumor shape |
| `fractal_dimension_mean` | Feature | Fractal dimension of tumor shape |

## 🎯 Objective

- Build a logistic regression model
- Investigate interaction effects
- Use Lasso regression to address multicollinearity
- Compare models using:
  - ROC curve and AUC
  - Likelihood Ratio Test
  - Residual Deviance

## 🧪 Models Used

- Logistic Regression
- Lasso Regression (with cross-validation)

