
# Bank Customer Churn Prediction 📊
"Customer Churn Prediction using Boosting Algorithms (AdaBoost, Gradient Boosting, LightGBM)"

**Predicting if bank customers will leave using machine learning models**  
Achieved ~86% accuracy with boosting algorithms!

## Project Overview

This project predicts customer churn (Exited = 1) in a bank dataset using classification models.

- **Dataset**: 10,000 rows with features like CreditScore, Age, Balance, Geography, etc.
- **Goal**: Compare different models and find the best one
- **Challenge**: Imbalanced data (only ~20% churn)

## Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- LightGBM

## Files in This Repo

- `CHURN_MODELLING PROJECT.ipynb` → Main notebook (code + results)
- `Churn_Modelling.csv` → Dataset
- `README.md` → This file

## Results Summary

| Model                | Test Accuracy | Notes                     |
|----------------------|---------------|---------------------------|
| Gradient Boosting    | 86.5%        | Best performance         |
| LightGBM             | 86.4%        | Fast and efficient       |
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
