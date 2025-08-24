# Credit-Card-Fraud-Detection---Machine-Learning
This project focuses on detecting fraudulent credit card transactions using Machine Learning techniques. Fraud detection is a crucial challenge in the financial industry, and the goal of this project is to build a predictive model that can differentiate between legitimate and fraudulent transactions with high accuracy.

The dataset was obtained from Kaggle and the implementation was guided by a tutorial from GeeksforGeeks.

# Tools & Libraries Used
Python

Pandas – Data handling & preprocessing

NumPy – Numerical operations

Matplotlib & Seaborn – Data visualization & insights

RandomForestClassifier – Machine Learning model

# About the Dataset

The dataset contains 284,807 transactions, of which 492 are fraudulent.

It is highly imbalanced, with fraud cases making up only 0.172% of all transactions.

Features are numerical and result from PCA transformations to protect confidentiality.

Dataset link:https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

# Project Workflow

# 1) Data Preprocessing

Loaded the dataset using Pandas

Handled imbalanced dataset issue using sampling techniques

# 2) Exploratory Data Analysis (EDA)

Visualized class distribution

Correlation analysis

Transaction patterns

# 3) Model Building

Implemented Random Forest Classifier

Trained the model on balanced data

# 4) Model Evaluation

Evaluated performance using Accuracy, Precision, Recall, and F1-score

Addressed the imbalance issue to reduce false negatives

# Results
Accuracy:  0.9995786664794073

Precision:  0.9743589743589743

Recall:  0.7755102040816326

F1 Score:  0.8636363636363636

Matthews Correlation Coefficient:  0.8690748763736589

Random Forest achieved strong results in distinguishing fraudulent transactions.

Proper handling of imbalance improved recall, ensuring fewer fraud cases were missed.

# References

Dataset: Kaggle : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

Guidance: GeeksforGeeks :https://www.geeksforgeeks.org/machine-learning/ml-credit-card-fraud-detection/
