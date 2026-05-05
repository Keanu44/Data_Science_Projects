# ❤️ Heart Disease Prediction (End-to-End Machine Learning Project)

![Project!_overview](..\Images\heart_disease.png)

## 📌 Overview

This project focuses on predicting the presence of heart disease using machine learning techniques. It covers the full ML workflow — from data exploration and visualization to model building, hyperparameter tuning, and evaluation.

The goal is to build a reliable classification model that can assist in early detection of heart disease.

---

## 🚀 Project Workflow

### 1. Data Loading

* Dataset: `heart-disease.csv`
* Loaded using Pandas
* Structured dataset with medical attributes

### 2. Exploratory Data Analysis (EDA)

* Checked data structure (`info()`, `describe()`)
* Identified class distribution
* Visualized relationships:

  * Heart disease vs sex
  * Age vs cholesterol
  * Age vs max heart rate
  * Chest pain types vs target
* Correlation matrix analysis

### 3. Data Preparation

* Split features (`X`) and target (`y`)
* Train-test split using `sklearn`

---

## 🤖 Models Used

The following models were trained and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Random Forest Classifier

A helper function was used to train and evaluate multiple models efficiently.

---

## 📊 Model Evaluation

Evaluation metrics used:

* Accuracy
* Confusion Matrix
* ROC Curve & AUC Score
* Classification Report:

  * Precision
  * Recall
  * F1-score

---

## ⚙️ Hyperparameter Tuning

### 🔹 RandomizedSearchCV

Used for:

* Logistic Regression
* Random Forest

### 🔹 GridSearchCV

* Applied on Logistic Regression for further optimization

---

## 📈 Final Model Performance

* Best model: **Logistic Regression (tuned)**
* Evaluated using:

  * Cross-validation accuracy
  * Precision
  * Recall
  * F1-score

---

## 🧠 Key Insights

* Certain features like **chest pain type, max heart rate, and age** show strong correlation with heart disease.
* Logistic Regression performed best after tuning.
* Proper hyperparameter tuning significantly improved model performance.

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-learn
