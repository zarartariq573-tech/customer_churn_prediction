# Customer Churn Prediction (Bank Customers)

## Objective

The objective of this project is to predict whether a bank customer is likely to leave the bank (churn) using historical customer data. This helps banks take proactive actions to retain customers.

## Approach

* Loaded and explored the Churn Modelling dataset
* Cleaned the dataset by removing irrelevant columns (RowNumber, CustomerId, Surname)
* Encoded categorical variables:

  * Gender using Label Encoding
  * Geography using One-Hot Encoding
* Split the dataset into training and testing sets
* Applied feature scaling using StandardScaler
* Trained a machine learning model using XGBoost Classifier
* Evaluated the model using accuracy and classification metrics
* Analyzed feature importance to understand key churn factors

## Results and Insights

* The XGBoost model achieved an accuracy of **81%**
* Important features influencing churn include:

  * Age
  * Account Balance
  * Credit Score
  * Geography
  * Number of Products
* Customers with higher age and lower engagement are more likely to churn
* Active members are less likely to leave the bank
* Feature importance analysis helps identify high-risk customers for targeted retention strategies
# customer_churn_prediction
