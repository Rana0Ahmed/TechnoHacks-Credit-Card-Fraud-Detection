# TechnoHacks-Credit-Card-Fraud-Detection
### Author : [Rana Ahmed](https://www.linkedin.com/in/rana-ahmed-3b2972246/)

<img src="https://www.customerservicemanager.com/wp-content/uploads/2020/05/credtcard.jpg" width="500">

## Table of Contents
- [Problem Statement](https://github.com/Rana0Ahmed/TechnoHacks-Credit-Card-Fraud-Detection#problem-statement)
- [Introduction](https://github.com/Rana0Ahmed/TechnoHacks-Credit-Card-Fraud-Detection#introduction)
- [Import Dependencies](https://github.com/Rana0Ahmed/TechnoHacks-Credit-Card-Fraud-Detection#import-dependencies)
- [Dataset](https://github.com/Rana0Ahmed/TechnoHacks-Credit-Card-Fraud-Detection#dataset)
- [Data Preprocessing](https://github.com/Rana0Ahmed/TechnoHacks-Credit-Card-Fraud-Detection#data-preprocessing)
- [Exploratory Data Analysis](https://github.com/Rana0Ahmed/TechnoHacks-Credit-Card-Fraud-Detection#exploratory-data-analysis)
- [Feature Engineering](https://github.com/Rana0Ahmed/TechnoHacks-Credit-Card-Fraud-Detection#feature-engineering)
- [Spliting the data](https://github.com/Rana0Ahmed/TechnoHacks-Credit-Card-Fraud-Detection#spliting-the-data)
- [Model Building](https://github.com/Rana0Ahmed/TechnoHacks-Credit-Card-Fraud-Detection#model-building)
- [Model Evaluation](https://github.com/Rana0Ahmed/TechnoHacks-Credit-Card-Fraud-Detection#model-evaluation)
- [Hyperparameter tuning](https://github.com/Rana0Ahmed/TechnoHacks-Credit-Card-Fraud-Detection#hyperparameter-tuning)
- [Scores](https://github.com/Rana0Ahmed/TechnoHacks-Credit-Card-Fraud-Detection#scores)

## Problem Statement
Fraud Transaction Detection.
## Introduction
This Jupyter Notebook presents a machine learning project for Credit Card Fraud Detection. The goal of this project is to detect fraudulent transactions from a dataset containing credit card transaction records.
## Import Dependencies
Import Necssaries Libraries used in this project.
## Dataset
The dataset used in this project could be found from [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). The dataset is divided into legitimate and fraudulent transactions.
## Data Preprocessing
Before building and training machine learning models, we perform essential data preprocessing steps, including handling missing data, data scaling...
## Exploratory Data Analysis
We conduct exploratory data analysis (EDA) to gain insights into the dataset. EDA involves data visualization and statistical analysis to understand the distribution of features and detect patterns.
## Feature Engineering
An part of building an effective fraud detection model. We create new features to improve the model's ability to distinguish between legitimate and fraudulent transactions.
## Spliting the data  
Spliting data using into training and testing Data
## Model Building
In this project, I used two algorithms : 
- Random Forest
- Adaboost
## Model evaluation
To evaluate the performance of our classifiers. I used metrics like precision, precision, recall, F1-score then visualized a Confusion matrix, and ROC-AUC to measure the effectiveness of the model in detecting fraudulent transactions.
## Hyperparameter tuning
By using Grid search CV to find the best combination of values of the hyperparameters searching in a multi-dimensional space.
## Scores
- **Random Forest Classifier**
    - Accuracy score --> 96%
    - AUC --> 0.959
- **Adaboost Classifier**
  - Accuracy score --> 97% 
  - AUC --> 0.967


