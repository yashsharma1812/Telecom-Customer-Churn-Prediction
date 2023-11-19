# Telecom-Customer-Churn-Prediction

## Introduction:
The Telecom Customer Churn Prediction project aims to address the critical challenge of retaining customers in the highly competitive telecommunications industry. Customer churn, or the loss of subscribers to competing services, can have a significant impact on revenue and profitability. By leveraging advanced analytics and machine learning techniques, this project seeks to identify patterns and factors that contribute to customer churn, ultimately enabling proactive measures to retain valuable customers.


## Objectives:

- Prediction Accuracy: Develop a robust predictive model that accurately forecasts the likelihood of a customer churning based on historical data and relevant features.
- Feature Analysis: Identify and analyze key features influencing customer churn, such as contract duration, usage patterns, tenure, and billing information.
- Model Interpretability: Strive for model interpretability to provide insights into the factors driving predictions, enabling telecom operators to make informed decisions and implement targeted retention 
  strategies.

## Methodology:

- Data Collection: Gather comprehensive data from various sources within the telecom ecosystem, ensuring a diverse and representative dataset for training and testing the model.
- Data Preprocessing: Cleanse and preprocess the data to handle missing values, outliers, and standardize formats. Perform exploratory data analysis (EDA) to gain insights into the dataset's characteristics.
- Feature Engineering: Identify and create relevant features that may influence customer churn. This includes deriving new metrics or transforming existing ones to enhance the predictive power of the model.
- Model Selection: Evaluate and compare the performance of different machine learning models, such as logistic regression, decision trees, random forests, to determine the most effective approach for 
  predicting customer churn.
- Model Training and Evaluation: Train the selected model on a subset of the data and evaluate its performance using metrics like accuracy, precision, recall, and area under the receiver operating 
  characteristic (ROC) curve.
- Hyperparameter Tuning: Fine-tune the chosen model's hyperparameters to optimize its predictive performance.


## Dataset:
https://www.kaggle.com/bhartiprasad17/customer-churn-prediction/data

## Observations From EDA:

1. 27 % of customers switched to another firm
2. Both genders behaved in similar fashion when it comes to migrating to another service provider/firm.
3. About 43% of customer with Month-to-Month Contract opted to move out as compared to 11% of customrs with One Year Contract and 3% with Two Year Contract.
4. Customers who use Fiber optic have high churn rate, this might suggest a dissatisfaction with this type of internet service. Customers having DSL service are majority in number and have less churn rate 
   compared to Fibre optic service.
5. Customers without dependents are more likely to churn.
6. Most customers churn due to lack of online security
7. Customers with Paperless Billing are most likely to churn.
8. Customers with no TechSupport are most likely to migrate to another service provider.


## Final Model:
We have used Logistic Regression, Decision Tree and Random Forest for Model Development. Based on the evaluation of models, we will select Logistic Regression for making predictions as it has accuracy of about 80% and better recall and precision value than the other two models.
