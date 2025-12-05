# Credit Card Fraud Detection — Machine Learning Project
## Problem

Financial institutions face increasing losses due to fraudulent credit card transactions.
The challenge becomes more complex when working with:

* A highly imbalanced dataset (fraud cases < 1%)

* Over 6 million real transaction records

* The need for fast, scalable, and accurate fraud detection

The objective was to develop a robust machine learning system that can accurately identify fraudulent transactions with minimal false positives.

## Solution

An end-to-end fraud detection pipeline was developed using advanced data processing and machine learning techniques:

1. Exploratory Data Analysis (EDA)

* Identified transaction patterns, anomalies, and fraud correlations

* Handled missing values, outliers, and time-based trends

* Visualized fraud vs. non-fraud distribution across key features

2. Class Imbalance Handling

* Applied SMOTE (Synthetic Minority Oversampling Technique)

* Balanced the dataset to improve model learning

* Compared undersampling & oversampling strategies

3. Machine Learning Models

* Multiple models were tested, including:

          * Logistic Regression

          * Random Forest

          * XGBoost (best performing)

* A full ML workflow was implemented:

          * Feature scaling

          * Train-test split

          * Hyperparameter tuning

          * Cross-validation

4. Evaluation

Models were evaluated using fraud-sensitive metrics:

* ROC-AUC

* Precision, Recall, F1-score

* Confusion Matrix

## Outcome

The project resulted in:

* ~99% ROC-AUC score using XGBoost, outperforming baseline models

* Highly precise fraud detection with minimal false alarms

* A scalable pipeline suitable for real-time deployment

* Actionable insights for improving fraud monitoring systems

This solution significantly strengthens fraud prevention strategies and helps reduce financial losses.

# Tools & Technologies

* Python

* Pandas, NumPy

* Scikit-learn

* XGBoost

* SMOTE (Imbalanced-learn)

* Matplotlib, Seaborn

* End-to-end ML Pipeline
