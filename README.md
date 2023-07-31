# Customer Churn Prediction Project

## Overview
This project is part of my data science portfolio and aims to predict customer churn for a telecom company. The goal is to develop a model that can accurately predict whether a customer is likely to churn or not. By identifying potential churners, the telecom company can take proactive retention measures to reduce customer churn and improve customer satisfaction.

## Dataset
The dataset used for this project is sourced from Kaggle and contains historical customer data from the telecom company. It includes various features such as customer demographics, call usage, and international plan status. The target variable is whether a customer churned (yes or no).

## Data Preprocessing
Before building the predictive model, the dataset underwent several preprocessing steps, including handling missing values, encoding categorical variables, and scaling numerical features. Exploratory data analysis (EDA) was also performed to gain insights into the distribution and relationship of features with churn.

## Model Building
For the churn prediction, a Random Forest classification model was employed due to its robustness and ability to handle complex datasets. The dataset was split into training and testing sets to evaluate the model's performance. Several evaluation metrics such as accuracy, precision, recall, and F1-score were used to assess the model's effectiveness.

## Model Evaluation
The Random Forest model achieved an accuracy of 93% on the test set, indicating its capability to accurately classify customers into churn and non-churn categories.

## Insights and Retention Strategies
Through the analysis of feature importance, we identified key factors that contribute to customer churn. These factors include the number of customer service calls, total international charges, and contract length. Based on these insights, we recommend the following retention strategies:

1. Improve Customer Service: Focus on reducing the number of customer service calls by addressing customer issues proactively and providing excellent customer support.

2. International Plan Offers: Introduce targeted offers or discounts for international plans to retain customers with a higher average of international charges.

3. Contract Incentives: Provide incentives or benefits for customers to opt for longer contract lengths to increase customer loyalty.

4. Personalized Promotions: Tailor marketing campaigns and promotions based on customer preferences and usage patterns to increase customer engagement and satisfaction.

## Conclusion
The Customer Churn Prediction project successfully developed a Random Forest model to predict customer churn with high accuracy. By understanding the factors influencing churn and implementing the recommended retention strategies, the telecom company can improve customer retention and overall business performance.

For more details and code implementation, please refer to the Google Colab Notebook provided in this repository.

## Acknowledgments
The dataset used for this project is sourced from Kaggle: https://www.kaggle.com/competitions/customer-churn-prediction-2020/data.
