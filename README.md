# Credit-Card-Fraud-Detection-CodSoft
# 💳 Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning. Fraud detection is a key application of data science in the financial sector. In this project, we analyze and build a model that can accurately distinguish between genuine and fraudulent credit card transactions.

---

## 📘 Project Overview

- **Objective**: To build a classification model that identifies fraudulent credit card transactions.
- **Dataset**: The dataset is highly imbalanced, with a small percentage of fraudulent transactions.
- **Approach**: Data preprocessing, exploratory data analysis (EDA), model training, and evaluation.

---

## 📁 Dataset

The dataset used includes:
- **Time**: Seconds elapsed between each transaction and the first transaction.
- **V1 to V28**: Result of PCA transformation for confidentiality.
- **Amount**: Transaction amount.
- **Class**: Target variable (0 = Not Fraud, 1 = Fraud)
- **Dataset Source**:[Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud/code?datasetId=310&sortBy=relevance)
---

## 🛠️ Technologies Used

- Python 🐍
- Pandas & NumPy 📊
- Matplotlib & Seaborn 📉
- Scikit-learn 🔍
- Machine Learning Algorithms (Logistic Regression, Random Forest, etc.)

---

## 🚀 Steps Performed

1. **Data Cleaning** – Handled missing data (if any), scaled values.
2. **EDA** – Visualized data imbalance, correlations, and feature importance.
3. **Resampling** – Used techniques like SMOTE to handle class imbalance.
4. **Model Building** – Trained and tested models with performance metrics.
5. **Evaluation** – Accuracy, Precision, Recall, F1-Score, ROC-AUC.

---

## 📈 Model Evaluation Metrics

- **Confusion Matrix**
- **ROC-AUC Curve**
- **Precision-Recall Curve**
- **Classification Report**

---

## ✅ Results

The model was able to effectively identify fraudulent transactions despite the dataset imbalance, achieving strong performance on key metrics such as precision and recall.

---
