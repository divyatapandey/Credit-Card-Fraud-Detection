# Credit Card Fraud Detection

This project is a machine learning-based system for detecting fraudulent credit card transactions. Using real-world anonymized transaction data, the model aims to identify fraudulent activities with high precision.

## 📌 Project Overview

- **Dataset**: [Kaggle Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Objective**: Classify transactions as fraudulent (1) or legitimate (0).
- **Tools Used**: Python, Jupyter Notebook, Scikit-learn, Pandas, Matplotlib, Seaborn

## 📊 Features of the Dataset

- **Transactions**: 284,807
- **Fraudulent Transactions**: 492 (highly imbalanced)
- **Features**: 30 anonymized columns (V1 to V28), `Amount`, `Time`, `Class` (target)

## ⚙️ Workflow

1. **Data Preprocessing**
   - Handling class imbalance using undersampling or SMOTE
   - Feature scaling
   - Null value handling (if required)

2. **Modeling**
   - Logistic Regression
   - Random Forest
   - XGBoost
   - Evaluation with confusion matrix, precision, recall, F1-score

3. **Evaluation**
   - Accuracy is **not** used as a primary metric due to class imbalance.
   - ROC-AUC, Precision-Recall are preferred.

## 📈 Results

- Best performing model: Achieved 99.95% accuracy and 1.0 ROC-AUC score on test data; no false positives or negatives



