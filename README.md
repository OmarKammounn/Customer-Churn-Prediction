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

This repository contains the work completed for the Customer Churn Prediction project, where the aim was to predict whether a telecommunications customer would churn or not. The concept of churning refers to customers switching to other providers. The project included the exploration of the dataset, data preprocessing, machine learning model training, predictions, and the analysis of results to comprehend customer churn patterns. The ultimate goal was to formulate effective strategies to mitigate customer churn and enhance customer loyalty.

## Dataset

The dataset utilized for this project comprises 4250 samples, each consisting of 19 features and a binary target variable "churn" (indicating whether the customer churned or not). These features encompass customer demographics, call details, charges, and service usage. The target variable "churn" signifies whether the customer churned (yes) or not (no).

The dataset can be accessed on Kaggle through the following link: https://www.kaggle.com/competitions/customer-churn-prediction-2020/data

## Project Scope and Reason

This project was undertaken during the final three weeks of the WBS Coding School Data Science Bootcamp. The scope of the project encompassed the end-to-end process of solving a real-world data science problem. This included the exploration of data, preprocessing, model training, evaluation, data visualization, insights generation, significance testing, and the formulation of actionable retention strategies.

The reason for selecting this project was to showcase proficiency in applying machine learning techniques to address a crucial business problem faced by telecommunications companies - customer churn. By accurately predicting churn and devising effective retention strategies, the goal was to demonstrate the value of data-driven decision-making and its potential impact on business sustainability.

## Project Steps

1. **Data Exploration and Preprocessing:** The project commenced with the exploration of the dataset, detection of missing values, and the execution of data preprocessing. This phase encompassed the handling of categorical variables, scaling of numerical features, and the preparation of data for subsequent model training.

2. **Model Training and Evaluation:** A random forest classifier was trained on the preprocessed training dataset. Utilizing cross-validation, the model's performance was assessed, and key metrics, such as accuracy, were calculated to gauge its predictive capability.

3. **Making Predictions:** After model training, predictions were generated on the test dataset provided by Kaggle.

4. **Data Visualization and Insights:** Utilizing the predictions, an array of plots and visualizations were generated to derive insights from the dataset. These visualizations facilitated the comprehension of relationships between distinct features and the target variable "churn." By comparing patterns of customers who churned and those who did not, potential churn factors were identified.

5. **Significance Testing:** To assess the significance of various features, significance tests were conducted to ascertain whether observed behavioral disparities between churned and non-churned customers were statistically significant or merely due to chance. This analysis provided valuable insights into the characteristics of churn customers.

6. **Devising Retention Strategies:** Capitalizing on insights derived from data visualization and significance testing, strategies for customer retention were devised. These strategies aimed to proactively identify customers at risk of churn and extend targeted incentives, discounts, or personalized offers to bolster customer loyalty and diminish churn.

7. **Conclusion and Recommendations:** The project culminated in a concise summary of findings, which included the effectiveness of the model in predicting customer churn, insights gleaned from data analysis, and recommended retention strategies. The culmination involved the presentation of results and insights to bootcamp peers and an experienced jury of instructors. Positive feedback during the presentation validated the project's significance and impact. Overall, the Customer Churn Prediction project underscored the significance of data-driven decision-making in curtailing churn and advancing business sustainability within the telecommunications domain.

## Evaluation Metric

Submissions for the Kaggle competition were evaluated based on the accuracy metric. Accuracy is computed as the ratio of correct predictions to the total number of test samples. Higher accuracy indicates superior model performance.

## Model Performance

The final random forest model achieved an accuracy of 93% on the test dataset. This outcome underscores the model's efficacy in forecasting customer churn within the telecommunications domain.

## Acknowledgements

Gratitude is extended to Kaggle for furnishing the dataset and hosting this engaging competition. Participation in this project has substantially elevated data science and machine learning proficiencies. The dedicated instructors and supportive peers who contributed to the success of this project and bootcamp are also sincerely acknowledged.

## Contact

For inquiries or feedback concerning this project, feel free to reach out.

Email: omar-kammoun@outlook.com
