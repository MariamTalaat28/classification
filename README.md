# Titanic Survival Prediction Model
# Problem Statement
The goal of this project is to develop a classification model that predicts whether a passenger survived the Titanic disaster based on key features such as age, gender, passenger class, and fare.

By leveraging machine learning techniques, we aim to analyze the historical dataset, extract meaningful insights, and build a robust predictive model to classify passengers as survivors or non-survivors.

# Business Problem Overview
The sinking of the Titanic in 1912 was one of the deadliest maritime disasters in history. Understanding the factors that influenced passenger survival can provide valuable insights into decision-making during emergencies.

Machine learning plays a crucial role in such predictive analytics, helping organizations across industries analyze historical data, uncover patterns, and make informed decisions. In this project, we apply a classification model to assess the likelihood of passenger survival, demonstrating how data-driven approaches can enhance predictions and decision-making.

# Understanding the Titanic Dataset
The dataset used for this project is sourced from the Kaggle Titanic dataset. It contains information on passenger demographics, ticket details, and survival outcomes.

Key features in the dataset include:

PassengerId: Unique identifier for each passenger

Survived: Target variable (1 = Survived, 0 = Did not survive)

Pclass: Passenger class (1st, 2nd, or 3rd)

Name: Passenger name

Sex: Gender

Age: Age of the passenger

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Ticket: Ticket number

Fare: Fare paid for the ticket

Cabin: Cabin number

Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

# Project Pipeline
The project workflow consists of the following steps:

The project workflow consists of the following steps:

# 1. Data Understanding & Preprocessing
Loaded the Titanic dataset and explored its structure.
Handled missing values and performed feature engineering.
Converted categorical variables into numerical form for model compatibility.
# 2. Exploratory Data Analysis (EDA)
Analyzed survival rates based on different passenger attributes.
Visualized key trends using histograms, bar plots, and correlation heatmaps.
Identified feature importance for classification.
# 3. Model Training & Evaluation
Selected Naïve Bayes as the primary algorithm for classification.
Split the dataset into training and testing sets.
Trained the model and fine-tuned hyperparameters.
Evaluated model performance using key metrics:
Accuracy: 79%
Precision: 91%
Recall: 75.9%
# 4. Model Insights & Key Findings
Gender played a crucial role in survival predictions (higher survival rate for females).
Passenger class significantly influenced survival chances (1st-class passengers had a higher survival rate).
Age and fare were important factors in determining survival probability.

Passenger class significantly influenced survival chances (1st-class passengers had a higher survival rate).

Age and fare were important factors in determining survival probability.
Conclusion


This project demonstrates how machine learning can be applied to historical datasets for predictive modeling. The Naïve Bayes classifier provided strong performance, highlighting key survival factors. Further improvements can be achieved by testing additional models, feature selection techniques, and advanced ensemble learning methods.
This project demonstrates how machine learning can be applied to historical datasets for predictive modeling. The Naïve Bayes classifier provided strong performance, highlighting key survival factors. Further improvements can be achieved by testing additional models, feature selection techniques, and advanced ensemble learning methods.
