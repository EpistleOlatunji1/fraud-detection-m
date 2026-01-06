# Fraud Detection System 
 Project Overview

This project develops a machine learning–based fraud detection system designed to identify potentially fraudulent banking transactions and support financial crime prevention, customer protection, and institutional risk monitoring. The system was built and validated using real-world–structured transaction data and modern class-imbalance handling techniques to reflect realistic banking fraud conditions.

The model generates probability-based fraud risk scores that can be used by banks for transaction screening, alert prioritization, and compliance reporting.

 # Objectives

Detect suspicious and fraudulent transactions with high reliability

Produce probability-based fraud risk scores for each transaction

Handle severe class imbalance common in real banking fraud data

Support financial stability, customer protection, and regulatory compliance

# Methodology

Algorithms: Balanced Random Forest, Logistic Regression, Decision Tree

Imbalance Handling: SMOTE oversampling and class-balanced learning

Data Structure: Transaction amount, account balance, anomaly scores, and behavioral risk indicators

Tools: Python, Pandas, NumPy, Scikit-learn, Imbalanced-learn

Validation: ROC Curve, Precision–Recall Curve, Confusion Matrix

# Model Performance (Validated)

ROC-AUC: 0.62 under extreme class imbalance (≈ 4.5% fraud rate)

Threshold Optimization: Model demonstrates highest fraud capture at low probability thresholds (0.20–0.35)

Evaluation: Confusion Matrix and PR Curve used for fraud governance and alert tuning

These results demonstrate the system’s ability to separate fraudulent from legitimate transactions under realistic banking conditions.

Applications

Banking transaction screening

Financial crime monitoring

Compliance and risk governance

Customer fraud protection systems

# Why This Matters

Financial fraud undermines economic stability and consumer trust.
This project demonstrates an applied, validated, and governance-aware AI system capable of supporting responsible banking operations and regulatory compliance.
