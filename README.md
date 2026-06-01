# Credit Risk Modelling

[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)](https://jupyter.org/)
[![Python](https://img.shields.io/badge/Python-3.7+-blue?logo=python)](https://www.python.org/)
[![CatBoost](https://img.shields.io/badge/CatBoost-Gradient_Boosting-green)](https://catboost.ai/)
[![Optuna](https://img.shields.io/badge/Optuna-Hyperparameter_Tuning-red)](https://optuna.org/)

## 📋 Project Overview

This repository contains a comprehensive **Credit Risk Modelling** project aimed at predicting the likelihood of loan default. The analysis includes data exploration, preprocessing, and building a robust classification model using **CatBoost**, a gradient boosting algorithm that handles categorical features effectively. Hyperparameter tuning is performed with **Optuna** to optimize model performance.

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `credit risk modelling.ipynb` | Main Jupyter Notebook containing all code for data analysis, feature engineering, model training, and evaluation |
| `credit_data.csv` | Dataset used for credit risk analysis (features include applicant demographics, credit history, loan details, etc.) |

## 🚀 Key Features

- **Exploratory Data Analysis (EDA)**: Understand data distributions, missing values, and relationships between features and default risk.
- **Data Preprocessing**: Handling missing values, encoding categorical variables, feature scaling where necessary.
- **CatBoost Modelling**: Training a gradient boosting model optimized for categorical data.
- **Optuna Hyperparameter Tuning**: Automated search for the best model parameters (learning rate, depth, iterations, etc.) to maximize ROC-AUC or minimize log-loss.
- **Model Evaluation**: Performance metrics including accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrix.

## 🛠️ Technologies Used

- **Python** (pandas, numpy, matplotlib, seaborn, scikit-learn)
- **CatBoost** – Gradient boosting on decision trees
- **Optuna** – Hyperparameter optimization framework
- **Jupyter Notebook** – Interactive development environment

## 📊 Dataset

The dataset `credit_data.csv` is included in this repository. Typical features in credit risk datasets include:

- Age, income, employment length
- Loan amount, loan purpose, interest rate
- Credit history length, number of delinquencies
- Existing debt, debt-to-income ratio
- Target variable: **Default** (1 = default, 0 = non-default)

> *Note: Refer to the notebook for exact column names and descriptions.*

## 📈 Model Performance

The final tuned CatBoost model achieved the following metrics (example placeholders – update with your actual results):

| Metric | Value |
|--------|-------|
| ROC-AUC | 0.85 |
| Accuracy | 0.82 |
| Precision (Default class) | 0.68 |
| Recall (Default class) | 0.72 |
| F1-score (Default class) | 0.70 |

## 🔧 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/ajayn3300/Credit-Risk-Modelling.git
   cd Credit-Risk-Modelling
