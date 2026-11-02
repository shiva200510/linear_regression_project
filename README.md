# Interest Rate Prediction Model

## 1. Project Overview

This project focuses on predicting loan interest rates using Machine Learning techniques. A Multiple Linear Regression model is developed to understand the relationship between customer financial information, credit history, loan details, and interest rates.

The project uses Python and statistical analysis techniques to build and evaluate a regression model.

## 2. Objective

The main objective of this project is to develop a Machine Learning model that predicts the interest rate of a loan based on various customer and loan-related features.

The model aims to:

- Analyze customer financial and credit-related information.
- Understand the factors that influence loan interest rates.
- Identify the relationship between independent variables and interest rates.
- Predict interest rates using Multiple Linear Regression.
- Evaluate the performance of the model using regression evaluation metrics.

## 3. Dataset Description

The dataset contains 260 records and 9 columns.

| Feature | Description |
|---|---|
| credit_score | Customer's credit score |
| annual_income | Customer's annual income |
| loan_amount | Amount of loan |
| dti | Debt-to-income ratio |
| emp_length_years | Years of employment |
| term_months | Loan repayment term in months |
| home_ownership | Customer's home ownership status |
| loan_purpose | Purpose of taking the loan |
| interest_rate | Target variable to be predicted |

## 4. Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Statsmodels
- Scikit-learn

## 5. Project Workflow

The following steps were performed:

1. Data Loading and Exploration
2. Data Inspection and Statistical Analysis
3. Missing Value Treatment using Median Imputation
4. Outlier Detection and Handling
5. Categorical Variable Encoding using Dummy Variables
6. Feature Selection
7. Multicollinearity Detection using VIF
8. Building a Multiple Linear Regression Model
9. Splitting Data into Training and Testing Sets (80:20)
10. Model Prediction
11. Model Evaluation
12. Residual Analysis

## 6. Machine Learning Algorithm

**Multiple Linear Regression (OLS)**

Multiple Linear Regression is a supervised Machine Learning algorithm used to predict a continuous numerical value based on multiple independent variables.

In this project, the model predicts loan interest rates using customer credit scores, income, loan amounts, employment information, and other loan-related factors.

Ordinary Least Squares (OLS) is used to estimate the regression coefficients.

## 7. Feature Selection and Statistical Analysis

The project uses:

- P-values to identify statistically insignificant features.
- Variance Inflation Factor (VIF) to detect multicollinearity.
- Feature selection to improve the regression model.

## 8. Model Evaluation

The model performance is evaluated using the following metrics:

- R-squared (R²)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)
- Mean Absolute Percentage Error (MAPE)

These metrics help measure how accurately the model predicts loan interest rates.

## 9. Residual Analysis

Residual analysis is performed to examine the difference between actual and predicted interest rates.

A Residuals vs Predicted plot is used to check the spread of errors and assess the homoscedasticity assumption.

## 10. Project Files

- `interest_rate_prediction.ipynb` – Jupyter Notebook containing data analysis, preprocessing, feature selection, model building, and evaluation.
- `loans - 1782056769161.csv` – Dataset used for training and testing the model.

## 11. Conclusion

This project demonstrates the application of Multiple Linear Regression in predicting loan interest rates using customer financial and loan-related information.

It provides insights into the relationship between credit scores, income, loan characteristics, and interest rates while demonstrating the practical application of Machine Learning and statistical analysis in financial data.

## 12. Author

**Shiva Tiwari**
