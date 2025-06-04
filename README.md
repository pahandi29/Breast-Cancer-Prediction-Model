# 🩺 Breast Cancer Prediction (ML Project)

This project applies machine learning techniques to predict **breast cancer mortality status** and estimate **survival time in months** for terminal patients. It was developed as part of a data mining and machine learning coursework assignment.

## 🔍 Project Objectives

- **Classification Task**: Predict whether a patient will survive or not using models like:
  - Logistic Regression (best-performing)
  - K-Nearest Neighbors
  - Naïve Bayes
- **Regression Task**: Estimate survival months for patients predicted not to survive using:
  - Fully grown and pruned Decision Tree Regressors

## ⚙️ Features

- Hyperparameter tuning with `GridSearchCV`
- Voting ensemble classifier (compared against base models)
- Evaluation metrics: AUC-ROC, F1-score, MAE, MSE
- Model explainability (e.g., prediction path for patient B002565)
- Ethical considerations in healthcare AI

## 📁 Files Included

- `Notebook_1.ipynb`: Data preprocessing and exploration  
- `Notebook_2.ipynb`: Classification models and evaluation  
- `Notebook_3.ipynb`: Regression models and prediction 
