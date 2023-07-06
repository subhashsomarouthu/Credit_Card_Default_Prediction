# Credit_Card_Default_Prediction
Predicting Credit Card Payment Defaulters using Classification Machine Learning Models

The purpose of this project is to develop a machine learning model which predicts credit card default payments for next month.

# Dataset
This dataset contains information on default payments, demographic factors, credit limit, history of payments, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

# Project Overview

Exploratory Data Analysis. 

Machine Learning Modeling.

Machine Learning Model explanation using SHAP

# Machine Learning Models Used:

Logistic Regression

Random Forest

SVM

XGBoost


# Model Comparison

In these four models Random Forest Classifier yielded promising results. It achieved a recall of 81%, indicating its ability to correctly identify a high percentage of defaulters. The f1 score, which considers both precision and recall, was 84%, indicating a good balance between the two metrics. The KS statistic, measuring the model's ability to distinguish between positive and negative classes, was 70%. These results were consistent across both the train and test datasets, indicating a reliable performance of the model.While Random Forest performed well, the tuned XGBoost model demonstrated higher precision and f1 score. However, it exhibited signs of overfitting, making it less suitable for deployment. SVM and Logistic Regression models yielded lower scores compared to Random Forest.


# Limitations
Best model Random Forest can only detect 81% of defaulters.
Used only 30,000 records, more data would lead to better prediction
If business want precission to be high, then XGBoost can be used rather than Random Forest


# Future Work
Other models could perform better.
Get more computational resources to tune Random Forest , SVM and XGBoost parameters.
Income of the person could have been more important feature, if given in the dataset

