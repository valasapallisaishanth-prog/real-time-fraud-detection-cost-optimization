**Real-Time Fraud Detection & Cost-Sensitive Optimization System
Project Overview**

Developed a production-style fraud detection system to identify fraudulent credit card transactions while minimizing expected financial loss.

**Business Objective**

Optimize fraud detection decisions based on:

False Negative Cost (Fraud Loss = $1000)

False Positive Cost (Customer Friction = $10)

The system selects the optimal probability threshold to minimize total expected financial loss.

**Models Compared**

Logistic Regression

Random Forest

Random Forest + SMOTE

XGBoost

LightGBM

**Key Results**
Model	Minimum Financial Loss
Logistic Regression	$15,030
Random Forest	$10,560
Random Forest + SMOTE	$9,920

Reduced expected fraud loss by ~34% compared to baseline.

**Techniques Used**

Imbalanced learning (SMOTE)

Cost-sensitive threshold optimization

ROC-AUC & PR-AUC evaluation

Financial loss minimization

Feature importance analysis

Real-time fraud decision engine

**Production Logic**

Score transaction

Apply optimized threshold

Flag high-risk transactions for review

Minimize expected financial loss

**Tech Stack**

Python, Scikit-Learn, XGBoost, LightGBM, Pandas, NumPy

Python, Scikit-learn, XGBoost, LightGBM, Pandas, NumPy

Then commit.
