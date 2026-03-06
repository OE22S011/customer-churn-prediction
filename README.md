# customer-churn-prediction
Logistic Regression model to predict customer churn using telecom data
# Customer Churn Prediction

A machine learning project to predict whether a telecom customer will churn (leave) using Logistic Regression.

## Problem Statement
Telecom companies lose revenue when customers leave. By predicting churn early, the company can take action to retain those customers.

## Dataset
- Source: BigML Telecom Churn Dataset
- Training set: 2666 rows
- Test set: 667 rows
- Target column: `Churn` (True / False)

## What I did
- Explored and visualized the data
- Preprocessed features (encoding, scaling)
- Trained a Logistic Regression model
- Evaluated using Accuracy, Confusion Matrix, ROC-AUC
- Identified top features driving churn

## Results
| Metric | Value |
|--------|-------|
| Model | Logistic Regression |
| Accuracy | ~85% |
| ROC-AUC | ~0.83 |

## Tools Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

## Files
| File | Description |
|------|-------------|
| `churn_logistic_regression.ipynb` | Main notebook with full code |
| `churn-bigml-80.csv` | Training dataset |
| `churn-bigml-20.csv` | Test dataset |
