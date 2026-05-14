# README — Employee Attrition Prediction using Decision Trees and Random Forest

![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Classification-blue)
![Python](https://img.shields.io/badge/Python-Data%20Science-yellow)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)

![Project Overview](../Images/Attrition.png)

## Project Overview

This project focuses on predicting employee attrition using supervised machine learning techniques. The notebook explores employee HR data through exploratory data analysis (EDA) and builds classification models using **Decision Tree** and **Random Forest** algorithms to identify employees who are more likely to leave the company.

The project aims to answer two important business questions:

* Can employee characteristics predict whether an employee is likely to leave the company?
* Which workplace factors contribute most to employee attrition?

---

## Executive Summary

* **Project Scope:** Built a complete machine learning classification workflow using HR employee attrition data.
* **Data Analysis:** Performed exploratory data analysis to identify patterns related to employee turnover.
* **Machine Learning Models:** Implemented Decision Tree and Random Forest classification models.
* **Evaluation:** Compared model performance using classification metrics and predictive analysis.
* **Business Outcome:** Generated actionable HR insights for improving employee retention strategies.

---

## Dataset Information

The dataset used in this project contains employee-related attributes such as:

* Age
* Monthly Income
* Job Satisfaction
* Years at Company
* Overtime
* Department
* Work-Life Balance
* Attrition Status

The target variable is:

* **Attrition** → Whether an employee left the company.

---

## Exploratory Data Analysis (EDA)

The notebook includes several visualizations and analyses to understand employee behavior and attrition trends.

### Key EDA Sections

* Attrition Distribution
* Overtime vs Attrition
* Monthly Income vs Attrition
* Job Satisfaction vs Attrition
* Years at Company vs Attrition

### Key Insights

* Employees working overtime showed higher attrition rates.
* Lower monthly income appeared more common among employees who left.
* Employees with lower job satisfaction were more likely to resign.
* Employee tenure influenced retention patterns.

---

## Machine Learning Workflow

### Models Used

* Decision Tree Classifier
* Random Forest Classifier

### Workflow Steps

1. Data Cleaning
2. Feature Selection
3. Data Preprocessing
4. Train-Test Split
5. Model Training
6. Model Evaluation
7. Prediction Analysis

---

## Tech Stack

* **Programming Language:** Python

* **Libraries Used:**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn
  * Scikit-learn

* **Environment:** Jupyter Notebook

* **Version Control:** Git & GitHub

---

## Project Structure

```bash
Employee-Attrition-Prediction/
│
├── Employee Attrition With Decision Trees and Random Forrest.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── README.md
```

---

## Model Evaluation

The project evaluates classification performance using:

* Accuracy Score
* Confusion Matrix
* Classification Report

The Random Forest model improves predictive stability by combining multiple decision trees, helping reduce overfitting compared to a single Decision Tree model.

---

## Business Value

This project demonstrates how machine learning can support HR analytics by:

* Identifying employees at risk of leaving
* Understanding factors affecting employee retention
* Assisting HR teams in data-driven decision making
* Improving workforce planning strategies

---

## Skills Demonstrated

* Exploratory Data Analysis (EDA)
* Data Visualization
* Machine Learning Classification
* Feature Engineering
* Model Evaluation
* Predictive Analytics
* HR Data Analysis

---