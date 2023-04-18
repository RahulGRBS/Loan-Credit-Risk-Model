# Credit-Risk-Model | Customer Loan

### Project Overview

Lending Agencies invest a lot of time and money into optimizing their pricing and accurately estimating the likelihood that customers will get default.Knowing all of this, advanced analytics is required in building a credit risk model to predict whether a customer will get default. As this is for practice purposes and ask is to use simple Logistic Regression or XGBoost. Objective is also to identify the best performing model, as measured by accuracy other performance performance metrices.

1. [Exploring Loan Data](#EDA)
2. [Logistic Regression for Defaults](#LogisticRegression)
3. [Gradient Boosted Trees Using XGBoost](#XGBoost)
4. [Model Implementation and Evaluation](#Evaluation)
5. [Data Files](#Data)
6. [Results](#results)


## Exploring and Preparing Loan Data <a name="EDA"></a>

The Understanding of the concept of credit risk and how it is calculated using cross tables and plots. Exploring the credit data, finding and visualizing outliers in credit data, Observe the risk with missing loan data and eventually dealing with missing data by replacing/removing missing credit data.

## Logistic Regression for Defaults<a name="LogisticRegression"></a>

The project is started with implementing logistic regression model which is a standard in risk modeling. Understanding the components of this model as well as how to score its performance. Once predictions are created, One can explore the financial impact of utilizing this model.

Implemented Logistic Regression for probability of default, Multivariant Logistic Regression, One-hot encoding credit data, credit model performance , default classification reporting, visually scoring credit models, thresholds selection with its impact and confusion matices.

## Gradient Boosted Trees Using XGBoost <a name="XGBoost"></a>

Decision trees are another standard credit risk model. Attempts have been made to go beyond decision trees by using the trendy XGBoost package in Python to create gradient boosted trees. XGBoost is a more regularized form of Gradient Boosting as it uses advanced regularization (L1 & L2) {The regularization’s objective is to counter overfitting models by lowering variance while increasing some bias. Lasso(L1) adds the sum of the absolute beta coefficients, and Ridge(L2) adds the sum of the beta coefficients squared}. This improves model generalization capabilities, After developing sophisticated models, stress testing is being done on their performance and discussion on column selection in unbalanced data.  

Again efforts have been made in column selection for credit risk, column importance and default prediction, visualizing column importance, model performance, cross validation for credit models, class imblance in the loan data and undersampled tree performance.

## Model Implementation and Evaluation <a name="Evaluation"></a>

After developing and testing two powerful machine learning models, key performance metrics are being used for comparision. Using advanced model selection techniques specifically for financial modeling one is selected. With that model, One can develop a business strategy and minimize expected loss.

The model evaluation involves comparing model reports/ROCs

## Data Files<a name="Data"></a>
The enclosed data set is the full, cleaned results of the Credit Risk Model implementation. There are three files besides this README:

1. Raw_Credit_Data.csv - CSV file with raw credit data
2. Credit_Data_Cleaned.csv - CSV file with cleaned data
3. Credit_Data_ReadyForModelling.csv - Credit Risk data ready for modelling.


## Results<a name="results"></a>

The main findings of the code can be found at the Medium blog.(Will share soon)
