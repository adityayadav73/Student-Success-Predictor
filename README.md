# Student Performance Prediction Pipeline
This repository contains a robust machine learning system designed to predict whether a student will "Pass" or "Fail" based on their academic metrics. The project achieves high reliability by implementing a clean data science workflow and preventing common pitfalls like data leakage.
# Project Overview
The core objective of this project is to build an end-to-end pipeline that handles raw data, processes it, and provides highly accurate predictions using Logistic Regression.
# Tech Stack
Language: Python 
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn.
# Workflow & Best Practices
Feature Engineering: Dropped the Final Grade column to prevent Target Leakage, ensuring the model learns from independent variables like study_hours and attendance_percentage.
Data Leakage Prevention: Followed industry standards by performing train_test_split before applying StandardScaler. The scaler was fitted only on the training set.
Visualization: Analyzed data distributions using scatter plots to confirm the linear relationship between features and student scores.
# Performance Metrics
The model exhibits exceptional performance on unseen test data:
Accuracy: 99.82%.
Confusion Matrix: Only 9 errors out of 5,000 samples (2 False Positives, 7 False Negatives).
ROC AUC Score: 0.9999, indicating perfect class separation.

# Author.
** Aditya Yadav **
