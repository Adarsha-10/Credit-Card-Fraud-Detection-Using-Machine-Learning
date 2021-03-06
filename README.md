# Credit-Card-Fraud-Detection-Using-Machine-Learning
## Dataset
https://www.kaggle.com/mlg-ulb/creditcardfraud

## Overview
Banking fraud, poses a significant threat to the key goal of many banks to retain high profitable customers.

In terms of substantial financial losses, trust and credibility, this is a concerning issue to both banks and customers alike.

With the rise in digital payment channels, the number of fraudulent transactions is also increasing in new and different ways.

In the banking industry, credit card fraud detection using machine learning is not only a trend but a necessity for them to put proactive monitoring and fraud prevention mechanisms in place. Machine learning is helping these institutions to reduce time-consuming manual reviews, costly chargebacks and fees as well as denials of legitimate transactions.

In this project we will predict fraudulent credit card transactions with the help of machine learning models.

We will use the dataset thae has been provided to us and includes credit card transactions made by European cardholders over a period of two days in September 2013


## Approach
We will follow these sequence of steps to complete this project

#### Load and understand the data

#### Exploratory Data Analysis

#### Data Preparation

 - Remove Unnecessary Columns
 - Train Test split
 - Scaling
 - Check Skewness in data
 - Mitigate skweness 

#### Model Building on Imbalanced Data

 - Logistic Regression
 - K-Nearest Neighbors(KNN)
 - Decision Tree
 - Random Forest
 - XGBoost
 ##### Select Best Model
 -Apply best hyperparameters
 -Predict on Test data
 -Important Features of best model
         
#### Model Building with balancing classes

##### RandomOverSamplimg
 -Handle Data Imbalance - RandomOverSampling
 
##### Model Building on Data Blanced with RandomOverSampling
 - Logistic Regression
 - K-Nearest Neighbors(KNN)
 - Decision Tree
 - Random Forest
 - XGBoost
##### SMOTE
-Handle Data Imbalance - SMOTE
##### Model Building on Data Blanced with SMOTE
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

##### ADASYN
-Handle Data Imbalance - ADASYN

##### Model Building on Data Blanced with ADASYN
- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

#### Select best method

 - Apply best hyperparameters
 - Predict on Test data
 - Important Features of best model
 - FPR,TPR & best threshold from the roc curve
