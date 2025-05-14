# Codsoft-Customer-Churn-Prediction
Task 3 – Customer Churn Prediction
Problem Statement
The goal is to build a predictive model to determine whether a customer will churn (leave the service) based on their demographics and usage behavior. This helps businesses proactively retain customers.
 Dataset

Source: Churn_Modelling.csv
Location: C:/Users/KEERTI/Downloads/Bank Customer Churn Prediction/Churn_Modelling.csv

Features Used

CreditScore
Geography
Gender
Age
Tenure
Balance
NumOfProducts
HasCrCard
IsActiveMember
EstimatedSalary

 Target

Exited – Indicates if the customer left the bank (1) or stayed (0)

Steps Performed

Loaded and cleaned the dataset
Encoded categorical variables (Geography, Gender)
Standardized numeric features
Split data into training and testing sets
Trained three models:

Logistic Regression
Random Forest Classifier
Gradient Boosting Classifier


Evaluated each model using:

Accuracy Score
Confusion Matrix
Classification Report



 Model Evaluation
Each model was tested for its accuracy and performance on predicting churn.
 Outcome
Successfully developed and evaluated machine learning models to predict customer churn with a focus on improving retention strategy.
 Libraries Used

pandas, numpy
matplotlib, seaborn
scikit-learn
