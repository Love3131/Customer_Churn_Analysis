# Customer_Churn_Analysis
**Project Overview**
This project focuses on predicting customer churn using various machine learning algorithms. The goal is to identify customers who are likely to leave the service, enabling proactive retention strategies.
Dataset
The dataset includes customer account information and monthly revenue data over the last 12 months, among other features relevant to churn behavior.

**Data Preparation**
Data cleaning and preprocessing were performed to handle missing values and categorical variables.
Features such as monthly average revenue and cashback amounts were analyzed.
The dataset was split into training and testing sets.
SMOTE (Synthetic Minority Over-sampling Technique) was applied to address class imbalance.

**Modeling Approaches
**Several models were trained and evaluated:

Logistic Regression
Random Forest
AdaBoost
Gradient Boosting
K-Nearest Neighbors (KNN)
Gaussian Naive Bayes

Each model was tuned using hyperparameter optimization to improve performance metrics such as precision, recall, and F1-score.

**Evaluation Metrics**
Model performance was assessed using:
Accuracy
Precision
Recall
F1-score
Confusion matrices

Special attention was given to balancing precision and recall for the minority churn class.
