# churn_customer_prediction_
ML model for predicting customer churn
Churn Customer Prediction using LightGBM
This repository contains a machine learning pipeline for predicting customer churn using the LightGBM algorithm. The project focuses on hyperparameter tuning, evaluation metrics, and robust preprocessing techniques.

🔍 Problem Statement
Customer churn refers to the loss of clients or subscribers. Identifying customers who are likely to leave a service helps businesses take proactive measures to improve customer retention.

⚙️ Technologies Used
Python

Jupyter Notebook

LightGBM: For fast and efficient gradient boosting

Scikit-learn: Preprocessing, model selection, metrics

NumPy and Pandas: Data manipulation

📊 Features of the Pipeline
Data Preprocessing

Train-test split using train_test_split()

Feature scaling with StandardScaler

Modeling

LightGBM Classifier (LGBMClassifier)

Grid Search for hyperparameter tuning with GridSearchCV

Evaluation using:

Accuracy

ROC AUC Score

Classification Report

Confusion Matrix

🧠 Model Details
Algorithm: LightGBM Classifier

Objective: Binary classification (binary)

Evaluation Metric: AUC (roc_auc)

Hyperparameter Tuning Grid:

learning_rate: [0.01, 0.05, 0.11]

num_leaves: [20, 31, 40]

max_depth: [1, 10, 20]

min_child_samples: [10, 20, 30]

subsample: [0.7, 0.8, 0.9]

colsample_bytree: [0.7, 0.8, 0.9]
