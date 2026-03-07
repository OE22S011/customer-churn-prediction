# 📊 Customer Churn Prediction

A machine learning project to predict whether a telecom customer will churn (leave) 
using multiple ML models and comparing their performance.

## 🎯 Problem Statement
Telecom companies lose revenue when customers leave unexpectedly.
By predicting churn early, the company can take action to retain those customers
and save revenue.

## 📁 Dataset
- **Source:** BigML Telecom Churn Dataset
- **Training set:** 2,666 rows
- **Test set:** 667 rows
- **Features:** 19 (usage patterns, call details, plan info)
- **Target column:** `Churn` (True / False)

## 🔬 What I did
- Explored and visualized the data (EDA)
- Checked class distribution and churn rate
- Preprocessed features (encoding Yes/No columns, StandardScaler)
- Trained **Logistic Regression** model
- Trained **Random Forest** model
- Compared both models using Accuracy, ROC-AUC, Confusion Matrix
- Identified top features driving churn

## 📈 Results

| Model | Accuracy | ROC-AUC |
|-------|----------|---------|
| Logistic Regression | 85.46% | 0.8261 |
| **Random Forest** | **95.20%** | **0.9241** |

✅ Random Forest outperformed Logistic Regression by **9.75%**

## 🛠️ Tools Used
- Python 3
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook
- Git & GitHub

## 📂 Files

| File | Description |
|------|-------------|
| `churn_logistic_regression.ipynb` | Main notebook — EDA, both models, comparison |
| `churn-bigml-80.csv` | Training dataset (80%) |
| `churn-bigml-20.csv` | Test dataset (20%) |

## 🚀 How to Run
1. Clone this repository
```
   git clone https://github.com/OE22S011/customer-churn-prediction.git
```
2. Open the notebook
```
   cd customer-churn-prediction
   jupyter notebook
```
3. Run all cells in `churn_logistic_regression.ipynb`

## 💡 Key Findings
- Customers with **International plan** are more likely to churn
- High **Customer service calls** strongly predict churn
- **Random Forest** handles this data much better than Logistic Regression
