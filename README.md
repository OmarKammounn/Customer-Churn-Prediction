# Predicting Customer Churn in Telecommunications - Kaggle Competition

## Table of Contents

- [Introduction](#introduction)
- [Dataset Description](#dataset-description)
- [Project Overview](#project-overview)
- [Project Steps](#project-steps)
- [Evaluation Metric](#evaluation-metric)
- [Model Performance](#model-performance)
- [Conclusion](#conclusion)
- [Acknowledgements](#acknowledgements)

## Introduction

This repository contains my submission for the "Predicting Customer Churn in Telecommunications" Kaggle competition. The competition aims to predict whether a customer will change telecommunications providers, known as "churning." The dataset contains various customer attributes and a target variable indicating whether the customer churned or not.

## Dataset Description

The dataset provided by Kaggle consists of 4250 samples, each containing 19 input features and one target variable "churn." The input features include customer attributes such as state, account length, area code, international plan, voice mail plan, call minutes and charges for different time periods, international calls, and the number of customer service calls. The target variable "churn" represents customer churn (yes or no).

## Project Overview

In this project, I aimed to build a predictive model that accurately classifies whether a customer is likely to churn based on the provided features. The goal was to develop a machine learning model that can assist telecommunications companies in identifying and retaining potential churn customers by proactively offering retention strategies.

## Project Steps

1. **Data Exploration and Preprocessing:** I started by exploring the dataset to gain insights into the data distribution and identify any missing values. I performed data preprocessing steps, including handling categorical variables and scaling numerical features.

2. **Model Selection and Hyperparameter Tuning:** I experimented with various machine learning algorithms, and after careful evaluation, I found that the random forest classifier performed best for this task. I used cross-validation with grid search to fine-tune the hyperparameters of the random forest model, optimizing its performance.

3. **Significance Testing:** I conducted significance tests on different features to understand if the differences in behavior between churn and non-churned customers were statistically significant or due to chance. This analysis provided valuable insights into the characteristics of churn customers.

4. **Model Training and Evaluation:** I trained the final random forest model on the training dataset and evaluated its performance using cross-validation. While I did not use a confusion matrix, I assessed the model's predictive power using evaluation metrics such as accuracy.

5. **Making Predictions:** I used the trained model to make predictions on the test dataset provided by Kaggle.

## Evaluation Metric

The Kaggle competition evaluated submissions based on the accuracy metric. Accuracy is calculated as the number of correct predictions divided by the total number of test samples. A higher accuracy indicates better model performance.

## Model Performance

The final random forest model achieved an accuracy of 93% on the test dataset. This demonstrates the effectiveness of the model in predicting customer churn in telecommunications.

## Conclusion

In conclusion, this project successfully addresses the challenge of predicting customer churn in the telecommunications industry. The developed random forest model can help companies identify customers at risk of churning and devise targeted retention strategies to reduce customer churn and improve customer satisfaction.

## Acknowledgements

I would like to thank Kaggle for providing the dataset and hosting this exciting competition. The opportunity to work on this project has allowed me to enhance my data science and machine learning skills significantly.

If you have any questions or feedback regarding this project, feel free to contact me.
