## Project overview

This project develops an end-to-end machine learning solution for predicting customer churn.
The goal is to identify customers who are likely to leave a service based on their demographic information, account details, services subscribed to, and billing information.
Customer churn prediction can help businesses identify customers at risk of leaving and take proactive retention measures.

## Objectives

- Explore and understand the customer churn dataset.
- Perform data cleaning and preprocessing.
- Conduct exploratory data analysis (EDA).
- Identify factors associated with customer churn.
- Engineer relevant features for machine learning.
- Train and compare machine learning models.
- Evaluate model performance using appropriate classification metrics.
- Identify the model that provides the best predictive performance.

- ## Dataset

The project uses the Telco Customer Churn dataset.

The dataset contains information about customers, including:

- Customer demographics
- Contract information
- Internet and phone services
- Payment methods
- Monthly charges
- Total charges
- Customer tenure
- Churn status

The target variable is:

`Churn`

where:

- `Yes` = Customer churned
- `No` = Customer remained

## Project Workflow

The project follows an end-to-end machine learning workflow:

1. Data Collection
2. Data Loading
3. Data Understanding
4. Data Cleaning
5. Exploratory Data Analysis
7. Data Preprocessing
8. Train-Test Split
9. Model Training models used are logistic regression and random forest
10. Model Evaluation used ROC-AUC,classification score, F1-score, Precision
11. Model Comparison
12. Final Model Selection

## Technologies used
1. Python
2. Pandas
3. NumPy
4. Matplotlib
5. Seaborn
6. Scikit-learn
7. Jupyter Notebook


## Key Business Questions

The analysis aims to answer questions such as:

1. What proportion of customers churn?
2. Which customer characteristics are associated with churn?
3. Does customer tenure influence churn?
4. How do contract types affect churn?
5. Does monthly spending relate to churn?
6. Which services are associated with higher churn?
7. Which machine learning model performs best?
