# Credit-Card-Fraud-Detection
Machine Learning project for detecting fraudulent credit card transactions.


# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset is highly imbalanced, so SMOTE was applied to balance the classes before training the models. Multiple classification algorithms were compared to identify the best-performing model.

---

## 🎯 Objective

- Detect fraudulent credit card transactions.
- Compare the performance of different machine learning models.
- Select the best model based on evaluation metrics.

---

## 📂 Dataset

- **Source:** Kaggle Credit Card Fraud Detection Dataset
- **Total Transactions:** 284,807
- **Features:** 30
- **Target Variable:** `Class`
  - **0** → Genuine Transaction
  - **1** → Fraudulent Transaction

> **Dataset Link:** https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## 🛠️ Project Workflow

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Preprocessing
- Feature Scaling
- Handling Class Imbalance using SMOTE
- Model Training
- Model Evaluation
- Model Comparison

---

## 🤖 Machine Learning Models Used

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

---

## 📊 Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|--------|----------|-----------|--------|----------|----------|
| Logistic Regression | 97.37% | 5.30% | 87.37% | 10.00% | 96.26% |
| Decision Tree | 99.75% | 36.42% | 66.32% | 47.01% | 83.06% |
| **Random Forest** | **99.94%** | **89.74%** | **73.68%** | **80.92%** | **95.55%** |
| XGBoost | 99.92% | 72.82% | 78.95% | 75.76% | **97.00%** |

---

## 🏆 Best Model

**Random Forest** achieved the best overall performance by providing the highest F1-score and precision while maintaining strong recall, making it the most suitable model for fraud detection.

---

## 📈 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- XGBoost



## 📌 Conclusion

Among all the models evaluated, **Random Forest** delivered the best balance between precision and recall, making it the most effective model for detecting fraudulent transactions while minimizing false positives.

---

## 👨‍💻 Author

**Vinut Singin**
