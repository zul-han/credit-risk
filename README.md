# Credit Risk Prediction

## Business Problem
Credit risk prediction is important in finance to help financial institution in predicting the likelihood of loan defaults. This is to minimize the financial losses and optimizing the capital allocation. Thus, this project focus on building the optimum  model to predict possible credit loan default.

## Data source

[Kaggle Credit Risk Dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset)

## Process
1. Loading the data
2. Data cleaning
3. Training the model
    - Logistic Regression
    - Random Forest
4. Evaluating the model
5. Saving the model

## Quick glance at the result

Comparison bar chart of baseline to tuned hyperparameter.

[![Comparing-parameters.png](https://i.postimg.cc/LXZ5NK8H/Comparing-parameters.png)](https://postimg.cc/R64vZYt8)

## Final result
- Random Forest is the finalized model for this project.
- Metric used: Recall
    - The objective of this project is to minimize the credit loan default
    - By focusing on recall (basically the sensitivity of the model) will reduce the chances of overlooking the default.
