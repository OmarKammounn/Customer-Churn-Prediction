# Customer Churn Prediction Project

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Project Scope and Reason](#project-scope-and-reason)
- [Project Steps](#project-steps)
- [Evaluation Metric](#evaluation-metric)
- [Model Performance](#model-performance)
- [Acknowledgements](#acknowledgements)
- [Contact](#contact)

## Overview

This repository contains our work for the Customer Churn Prediction project, where we aimed to predict whether a telecommunications customer will churn or not. Churning refers to the process of customers switching to other providers. The project involved exploring the dataset, preprocessing the data, training a machine learning model, making predictions, and analyzing the results to understand customer churn patterns. The goal was to develop effective retention strategies to reduce customer churn and improve customer loyalty.

## Dataset

The dataset used for this project includes 4250 samples, each with 19 features and a binary target variable "churn" (indicating whether the customer churned or not). The features include customer demographics, call details, charges, and service usage. The target variable "churn" denotes whether the customer churned (yes) or not (no).

The dataset can be accessed on Kaggle through the following link: https://www.kaggle.com/competitions/customer-churn-prediction-2020/data

## Project Scope and Reason

This project was undertaken during the final three weeks of the WBS Coding School Data Science Bootcamp. The scope of the project encompassed the end-to-end process of solving a real-world data science problem. It included data exploration, preprocessing, model training, evaluation, data visualization, insights generation, significance testing, and the development of actionable retention strategies.

The reason for selecting this project was to demonstrate our proficiency in applying machine learning techniques to solve a critical business problem faced by telecommunications companies - customer churn. By successfully predicting churn and developing effective retention strategies, we aimed to showcase the value of data-driven decision-making and its impact on business sustainability.

## Project Steps

1. **Data Exploration and Preprocessing:** We began by exploring the dataset, checking for missing values, and performing data preprocessing. This step involved handling categorical variables, scaling numerical features, and ensuring the data was ready for model training.

2. **Model Training and Evaluation:** We trained a random forest classifier on the preprocessed training dataset. Using cross-validation, we evaluated the model's performance and calculated key metrics, such as accuracy, to assess its predictive power.

3. **Making Predictions:** After training the model, we used it to make predictions on the test dataset provided by Kaggle.

4. **Data Visualization and Insights:** With the predictions, we created various plots and visualizations to gain insights into the dataset. These visualizations helped us understand the relationships between different features and the target variable "churn." By comparing churn and non-churned customers' patterns, we identified potential reasons for churn.

5. **Significance Testing:** To investigate the significance of different features, we conducted significance tests to determine if the observed differences in behavior between churn and non-churned customers were statistically significant or due to chance. This analysis provided valuable insights into the characteristics of churn customers.

6. **Developing Retention Strategies:** Leveraging the insights gained from data visualization and significance testing, we developed customer retention strategies. These strategies aimed to proactively identify customers at risk of churning and offer targeted incentives, discounts, or personalized offers to encourage customer loyalty and reduce churn.

7. **Conclusion and Recommendations:** In the final step, we summarized the project findings, including the model's effectiveness in predicting customer churn, insights gained from data analysis, and the recommended retention strategies. The culmination of the project involved presenting the results and insights to our bootcamp classmates and a jury consisting of experienced instructors. The positive feedback and validation received during the presentation reinforced the significance and impact of the project. Overall, the Customer Churn Prediction project demonstrated the value of data-driven decision-making in reducing churn and enhancing business sustainability in the telecommunications industry.

## Evaluation Metric

The Kaggle competition evaluated submissions based on the accuracy metric. Accuracy is calculated as the number of correct predictions divided by the total number of test samples. A higher accuracy indicates better model performance.

## Model Performance

The final random forest model achieved an accuracy of 93% on the test dataset. This demonstrates the effectiveness of the model in predicting customer churn in telecommunications.

## Acknowledgements

We would like to thank Kaggle for providing the dataset and hosting this exciting competition. The opportunity to work on this project has allowed us to enhance our data science and machine learning skills significantly. We would also like to express our sincere gratitude to all of the dedicated instructors and supportive classmates who were instrumental in making this project and Bootcamp a success.

## Contact

If you have any questions or feedback regarding this project, feel free to contact us.
Email: omar-kammoun@outlook.com
