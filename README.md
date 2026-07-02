# Women Credit Score Prediction

## Project Overview

This project focuses on predicting credit card payment default among female customers using machine learning techniques. 
The objective is to identify clients with a high probability of default, allowing financial institutions to improve credit risk assessment and support more informed lending decisions.
The project includes data preprocessing, feature engineering, class imbalance handling, model development, and performance evaluation using multiple classification algorithms.

## Business Problem

Credit card default represents a significant financial risk for banks and lending institutions.
Accurately identifying customers who are likely to miss future payments enables organizations to:

- Reduce financial losses.
- Improve credit approval decisions.
- Develop targeted risk management strategies.
- Increase portfolio profitability.

---

## Dataset

- **Source:** UCI Machine Learning Repository – Default of Credit Card Clients
- **Population:** Female credit card clients only
- **Target Variable:** Default payment next month (Yes/No)

## Technologies

- Python
- Pandas
- NumPy
- Seaborn
- Scikit-learn
- XGBoost
- Matplotlib
- Imbalanced-learn (SMOTE)

## Methodology

The project followed these main stages:

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Correlation Analysis
5. Class Imbalance Treatment using SMOTE
6. Model Training
7. Model Evaluation
8. Model Comparison


## Feature Engineering

Several new variables were created to improve model performance, including:

- Number of delayed payments
- Number of on-time payments
- Average payment ratio
- Credit utilization
- Log transformations of financial variables

---

## Machine Learning Models

The following models were trained and compared:

- Logistic Regression
- Random Forest
- XGBoost
---

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC AUC

Special attention was given to Recall, as identifying customers likely to default is more valuable than maximizing overall accuracy.

---

## Results

The best-performing model achieved strong predictive performance while maintaining good recall for the minority class after applying SMOTE.

Key findings include:

- Payment history is the strongest predictor of default.
- Feature engineering significantly improved model performance.
- Handling class imbalance increased the ability to detect risky customers.

---

## Repository Structure

```
women-credit-score-model/
│
├── README.md
├── notebooks/
├── data/
├── images/
├── requirements.txt
└── results/
```

---

## Future Improvements

Potential improvements include:

- Hyperparameter optimization
- Explainable AI using SHAP values
- Deployment as a web application
- Integration with SQL databases
- Real-world banking datasets

---

## Author

**Abigail Chirinos**

Data Analytics | Credit Risk | Machine Learning | Python | SQL
