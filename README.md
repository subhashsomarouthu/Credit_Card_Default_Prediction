
# Credit Card Default Prediction

## Table of Contents
1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Models Used](#models-used)
4. [Evaluation Metrics](#evaluation-metrics)
5. [How to Execute](#how-to-execute)
6. [Conclusion and Future Considerations](#conclusion-and-future-considerations)

## Introduction

This project aims to predict the likelihood of customer defaulting on their credit card payments in Taiwan. Predicting the estimated probability of default is valuable for risk management purposes, providing insights beyond binary classification.

**Business Objective:**

The goal is to predict the likelihood of customers defaulting on their credit card payments in Taiwan. This prediction is essential for risk management purposes.

## Dataset

The dataset used in this project contains valuable information related to credit card payments, customer demographics, and payment history. It serves as the foundation for developing predictive models for credit card payment defaults. It can be found in this [Link](https://docs.google.com/spreadsheets/d/1WSzAlD27mGG99sqCRERbHWOxZiyr8TUq/edit?usp=sharing&ouid=114817895883394277771&rtpof=true&sd=true)

## Models Used

To achieve our goal, I explored and evaluated several machine learning models:

1. **Logistic Regression:** A fundamental model for binary classification tasks, providing insights into the probability of credit card defaults.

2. **Random Forest:** A powerful ensemble model that combines multiple decision trees to make accurate predictions. Random Forest excels in capturing complex patterns in the data.

3. **Support Vector Machine (SVM):** A model capable of finding the optimal hyperplane to separate data points, often used for binary classification tasks.

4. **XGBoost Classifier:** A gradient boosting algorithm known for its high predictive accuracy and versatility.

## Evaluation Metrics

Model performance was assessed using the following evaluation metrics:

- **Recall:** A crucial metric for identifying defaulters, measuring the ability to correctly identify positive cases.
- **F1 Score:** A balanced metric considering both precision and recall, providing an overall measure of model performance.
- **KS Statistic:** A metric measuring the model's ability to distinguish between positive and negative classes, important for credit risk assessment.

## How to Execute

To execute this project and make predictions for credit card payment defaults, follow these steps:

1. Open the Jupyter Notebook file named `Credit_Card_Default_Prediction.ipynb`.
2. Execute the notebook cell by cell to load and preprocess the data, train the machine learning models, and make predictions.
3. The notebook provides detailed insights into data exploration, feature engineering, model training, and evaluation.

## Conclusion and Future Considerations

In conclusion, this project successfully developed a machine learning model for credit card payment default prediction. The project addressed the challenge of imbalanced data, explored important features, and evaluated multiple models. The chosen Random Forest model provides reliable predictions, and with ongoing monitoring and evaluation, it can be effectively deployed to minimize the risk of credit card payment defaults.

Future considerations for enhancing this project include:

- Continuous monitoring and model updating to adapt to changing patterns.
- Exploring additional data sources to improve predictive accuracy.
- Implementing real-time fraud detection systems for proactive risk management.

Feel free to reach out for any concerns [LinkedIn](www.linkedin.com/in/subhash-somarouthu).

