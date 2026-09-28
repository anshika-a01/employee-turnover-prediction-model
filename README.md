# 👥 Employee Turnover Prediction

A machine learning solution designed to predict employee attrition risk and identify retention drivers from HR data.

## 🎯 Overview
- **Objective:** Predict employee turnover (`Attrition = 1/0`) to enable early retention interventions.
- **Algorithms Evaluated:** Logistic Regression, Decision Tree, Random Forest, K-Nearest Neighbors, and XGBoost.
- **Best Overall Balance:** **Logistic Regression** achieved the highest F1-Score (0.449) and a balanced Recall (0.511).

## 🛠️ Tech Stack
- **Python:** `pandas`, `numpy`, `scikit-learn`, `xgboost`

## 📊 Model Comparison

| Model | Accuracy | Precision | Recall | F1 Score |
| :--- | :---: | :---: | :---: | :---: |
| **Logistic Regression** | **0.799** | **0.400** | **0.511** | **0.449** |
| Decision Tree | 0.752 | 0.309 | 0.447 | 0.365 |
| Random Forest | 0.799 | 0.342 | 0.277 | 0.306 |
| K-Nearest Neighbors | 0.626 | 0.226 | 0.553 | 0.321 |
| XGBoost | 0.810 | 0.371 | 0.277 | 0.317 |
