Credit Card Fraud Detection using Machine Learning

This project applies data science and machine learning techniques to detect fraudulent credit card transactions. It was developed as part of a Data Science term paper and demonstrates the process of exploratory data analysis (EDA), model training, and evaluation.

Dataset: https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The dataset used in this project is the Credit Card Fraud Detection dataset
 from Kaggle.
It contains 284,807 transactions made by European cardholders in September 2013, including 492 frauds (0.172%). The dataset is highly imbalanced.
Each transaction includes 30 features: 28 anonymized PCA-transformed components, and two original features (Time and Amount). The target variable Class indicates whether a transaction is legitimate (0) or fraudulent (1).

Project Overview

Exploratory Data Analysis (EDA):

Examined class distribution and transaction amount patterns.

Compared fraud and non-fraud transactions using visualizations and statistical tests.

Investigated selected PCA features for distribution differences.

Data Preprocessing:

Scaled numeric features using StandardScaler.

Split the dataset into training and test sets with stratified sampling.

Applied SMOTE to balance classes in the training data.

Modeling and Evaluation:

Trained Logistic Regression, Random Forest, and Logistic Regression with SMOTE.

Tuned Random Forest using GridSearchCV for optimal parameters.

Compared models using precision, recall, F1-score, ROC-AUC, and Precision-Recall curves.

Analyzed feature importance to identify the most influential PCA components (V14, V10, and V4).
