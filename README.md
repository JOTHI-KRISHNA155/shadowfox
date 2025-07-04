# shadowfox
  # 🏠 Housing Price Prediction using XGBoost

This project uses the **XGBoost Regressor** to predict housing prices based on features from a housing dataset. The model is optimized using **GridSearchCV** and evaluated with **R² Score** and **Mean Squared Error (MSE)**. It includes data preprocessing, visualization, model training, and feature importance analysis.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [Dataset](#-dataset)
- [Requirements](#-requirements)


---

## 🔍 Overview

Predicting housing prices is a classic regression problem that is useful for real estate valuation. This project builds a machine learning pipeline using XGBoost and Scikit-learn that performs:

- Data loading and preprocessing
- Feature scaling and visualization
- Model training with hyperparameter tuning
- Evaluation and visualization

---

## 🚀 Features

✅ Load and clean the dataset  
✅ Visualize feature correlations using heatmaps  
✅ Standardize features using `StandardScaler`  
✅ Split data into training and test sets  
✅ Hyperparameter tuning using `GridSearchCV`  
✅ Evaluate the model using R² and MSE  
✅ Plot actual vs predicted prices  
✅ Visualize feature importance

---

## 🧾 Dataset

- **File Name**: `HousingData.csv`
- **Target Column**: `MEDV` – Median value of owner-occupied homes (in $1000s)
- **Type**: Supervised regression

You must download or place `HousingData.csv` in the project directory before running the code.

## Sample Output
✅ Best Hyperparameters: {'learning_rate': 0.1, 'max_depth': 4, 'n_estimators': 200, 'subsample': 0.7}

📈 Cross-Validation R2 Score: 0.668 ± 0.138

📊 Final Evaluation on Test Set:
Mean Squared Error: 4.85
R² Score: 0.934

## 📦 Requirements

Install the required packages with pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost


