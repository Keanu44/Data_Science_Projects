
# Telecom Customer Churn Prediction using K-Nearest Neighbours (KNN)

![Project Overview](../Images/customer%20churn.jpg)

**This machine learning project analyzes telecom customer behavior using real-world customer data to predict churn risk using K-Nearest Neighbours (KNN) classification.**

---

# Executive Summary

- **Project Scope:** Built a predictive churn classification model using customer account and billing information.
- **Modeling:** Implemented K-Nearest Neighbours (KNN) with hyperparameter tuning and feature scaling.
- **Outcomes:** Identified key customer behaviors associated with churn including contract type, tenure, and monthly charges.

---

# Tech Stack

- **Language Used:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Machine Learning:** K-Nearest Neighbours (KNN)
- **Development Environment:** Jupyter Notebook
- **Version Control:** Git & GitHub

---

# Analysis Overview

## Data Preparation
- Converted TotalCharges to numeric format
- Handled missing values
- Encoded categorical variables
- Scaled features using StandardScaler

## Exploratory Data Analysis
- Churn distribution analysis
- Contract type segmentation
- Customer tenure analysis
- Monthly charges comparison

## Machine Learning Workflow
- Train-test split
- KNN classification
- K value optimization
- Error rate analysis

---

# Key Insights

- Month-to-month contract customers demonstrated the highest churn rates.
- Customers with shorter tenure were significantly more likely to leave.
- Higher monthly charges correlated with increased churn probability.
- The optimal K value was identified as:
## K = 35

indicating broader customer behavior patterns improved model stability.

---

# Model Evaluation

The model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report
- Error Rate Optimization

---

# Business Impact

This analysis can help telecom companies:
- Reduce customer churn
- Improve retention campaigns
- Identify high-risk customers early
- Increase customer lifetime value

---