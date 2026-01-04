
# Bank Customer Churn Prediction 📊
"Customer Churn Prediction using Boosting Algorithms (AdaBoost, Gradient Boosting, LightGBM)"

**Predicting if bank customers will leave using machine learning models**  
Achieved ~86% accuracy with boosting algorithms!

# Overview

This project focuses on predicting customer churn for a bank using machine learning techniques. Customer churn refers to customers leaving the bank (e.g., closing accounts). The goal is to identify at-risk customers based on historical data, enabling proactive retention strategies.
The project uses a dataset of 10,000 customer records and implements several classification models, including boosting algorithms (AdaBoost, Gradient Boosting, LightGBM) and other classifiers (KNN, SVC). Data preprocessing, model training, evaluation, and comparison are performed in a Jupyter Notebook.
Key objectives:

Analyze factors influencing churn (e.g., credit score, age, balance).
Build and evaluate models to predict churn with high accuracy.
Compare model performances to select the best one.

Dataset
The dataset (Churn_Modelling.csv) contains the following features:

RowNumber: Unique row identifier.
CustomerId: Unique customer ID.
Surname: Customer's last name (dropped during modeling).
CreditScore: Customer's credit score.
Geography: Country of residence (France, Spain, Germany; label-encoded).
Gender: Male/Female (label-encoded).
Age: Customer's age.
Tenure: Years as a bank customer.
Balance: Account balance.
NumOfProducts: Number of bank products used.
HasCrCard: Has a credit card (1/0).
IsActiveMember: Active member (1/0).
EstimatedSalary: Estimated annual salary.
Exited: Target variable (1 = churned, 0 = retained).

Source: The dataset is publicly available (e.g., from Kaggle's Bank Customer Churn dataset).

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
  

## Files in This Repo

- `CHURN_MODELLING PROJECT.ipynb` → Main notebook (code + results)
- `Churn_Modelling.csv` → Dataset
- `README.md` → This file

## Results Summary

| Model                | Test Accuracy | Notes                     |
|----------------------|---------------|---------------------------|
| AdaBoost             | 86.0%        | Good baseline            |
| SVC                  | 86.4%        | Low overfitting          |
| KNN                  | 83.5%        | More overfitting         |

Boosting models worked best!

## What I Learned

- How to preprocess data (encoding, scaling)
- Comparing multiple ML models
- Dealing with class imbalance (need to improve recall next!)

Future ideas: Add SMOTE for imbalance, tune hyperparameters.

## How to Run

1. Clone the repo
2. Install: `pip install pandas scikit-learn lightgbm`
3. Open the notebook in Jupyter or VS Code

Thanks for visiting! Feedback welcome 🚀

Connect on LinkedIn: [https://www.linkedin.com/in/sahil-thakur-880718352/]


