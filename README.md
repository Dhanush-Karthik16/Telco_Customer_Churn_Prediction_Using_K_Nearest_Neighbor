# 📉 Telco Customer Churn Prediction Using K-Nearest Neighbors Classifier

This project implements a K-Nearest Neighbors (KNN) classification model to predict whether a customer is likely to churn based on their account and service usage data. The model is trained using Telco customer data and evaluated using accuracy and a confusion matrix.

---

## 📁 Dataset

- **File**: `WA_Fn-UseC_-Telco-Customer-Churn.csv`
- **Source**: [Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Features**:  
  - Demographics: `gender`, `SeniorCitizen`, `Partner`, `Dependents`  
  - Services: `PhoneService`, `InternetService`, `StreamingTV`, etc.  
  - Account Info: `Tenure`, `Contract`, `MonthlyCharges`, etc.  
- **Target**: `Churn` (Yes/No)

---

## 🎯 Project Objectives

- Handle and encode categorical data for modeling
- Build a **K-Nearest Neighbors (KNN)** model to classify churn status
- Evaluate model using accuracy score and confusion matrix

---

## 🧪 Workflow Summary

### ✅ Data Preprocessing
- Checked for missing values
- Applied **Label Encoding** to all categorical columns
- Split data into:
  - Features (`x`)
  - Target (`y`)

### ✅ Model Training
- Split the dataset:
  - 80% training
  - 20% testing
- Trained a **KNeighborsClassifier** with:
  - `n_neighbors = 100`

### ✅ Model Evaluation
- Evaluated using:
  - `accuracy_score`
  - `confusion_matrix`

---

## 📊 Model Performance

| Metric       | Value        |
|--------------|--------------|
| Model Used   | KNeighborsClassifier |
| Accuracy     | ✅ *Displayed in output* |
| Confusion Matrix | ✅ *Displayed in output* |

> The model helps predict which customers are likely to churn based on their usage patterns and service attributes.

---

## 🔧 Technologies Used

- **Python 3.11**
- **Pandas & NumPy**
- **Scikit-learn (sklearn)** – For preprocessing, modeling, and evaluation

---

