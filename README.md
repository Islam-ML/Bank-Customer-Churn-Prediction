🏦 Bank Customer Churn Prediction
📄 Project Overview | نبذة عن المشروع
[English]
This project focuses on predicting whether a bank customer will stay or leave the bank (churn) based on demographic and financial data. The goal is to help the bank take proactive measures to retain customers. The project covers the entire data science pipeline from EDA to model deployment selection.

Language: Python 🐍
Data Manipulation: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Machine Learning: Scikit-Learn, XGBoost
Deep Learning: TensorFlow / Keras (ANN)
Imbalance Handling: SMOTE (Synthetic Minority Over-sampling Technique)
🔍 Key Steps | الخطوات الرئيسية
Exploratory Data Analysis (EDA): Analyzing correlations and feature distributions.
Data Preprocessing: Handling missing values, One-Hot Encoding for categorical features, and StandardScaler.
Model Training: Implementing and comparing 5 algorithms:
Artificial Neural Networks (ANN)
Logistic Regression
Random Forest
Support Vector Machine (SVM)
XGBoost Classifier
Handling Imbalance: Applied SMOTE to improve recall for the minority class.
🏆 Results | النتائج
After extensive testing and hyperparameter comparison, the XGBoost Classifier achieved the best balance between accuracy and recall, making it the selected model for this problem with an accuracy of ~86.95%.
