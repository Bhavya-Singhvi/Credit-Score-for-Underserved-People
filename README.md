# Credit-Score-for-Underserved-People
This project focuses on building a Credit Scoring Model for underserved populations using Machine Learning techniques. The objective is to predict whether a customer is creditworthy or not based on various behavioral and financial factors such as age, income, recharge patterns, freelance rating, and location stability.

Since real-world datasets were not available for this domain, a synthetic dataset was generated that closely mimics realistic scenarios.

Dataset
A synthetic dataset was generated consisting of the following features:

Age — Age of the customer

Mobile Recharge Level — Spending behavior on mobile recharge (High, Medium, Low)

Freelance Rating — Rating based on freelancing activity

Location Changes Per Month — Mobility of the customer

Monthly Income — Income in thousands

Creditworthy — Target Variable (Yes / No)

Data generation was performed using Python's randomization techniques while ensuring logical relations between features.

Methodology
Models Implemented:
Logistic Regression

Support Vector Machine (SVM)

Random Forest

Decision Tree

K-Nearest Neighbors (KNN)

Ensemble Learning:
A Voting Classifier (Hard Voting) was implemented combining the predictions of Logistic Regression, Random Forest, and SVM to improve the accuracy and robustness of the model.

Evaluation Metrics
The models were evaluated using:

Accuracy Score

Classification Report

Confusion Matrix

ROC Curve & AUC Score

ROC Curve:
The ROC curve was plotted to visualize the trade-off between the True Positive Rate (TPR) and False Positive Rate (FPR). The Area Under the Curve (AUC) was found to be 0.92, indicating excellent performance of the ensemble model.
