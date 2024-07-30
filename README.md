# Customer Lifetime Value Prediction and Analysis for Decathlon
Welcome to the Customer Lifetime Value (CLV) prediction and analysis project for Decathlon. This project aims to predict the CLV of customers using various machine learning techniques and analyze the factors affecting CLV.
## Introduction
Customer Lifetime Value (CLV) is a key metric that estimates the total revenue a business can reasonably expect from a single customer account throughout their relationship. Accurately predicting CLV helps businesses strategize marketing, sales, and customer service efforts effectively.

This project uses Decathlon's customer data to build predictive models for CLV and analyze the contributing factors. The project is structured to provide an end-to-end solution from data preprocessing.
## Data Collection
The data used in this project includes customer transactions, demographics, and engagement metrics. The dataset is collected from kaggle and online websites.
## Data Cleaning
Data cleaning involved handling missing values, removing duplicates, correcting inconsistencies, and formatting the data for analysis. This step ensured that the data is accurate and ready for feature engineering and modeling.
## Feature Engineering
Feature engineering involved creating new features that will help in predicting CLV. In this project, we use the RFM (Recency, Frequency, Monetary) analysis approach to create features:
- Recency: How recently a customer made a purchase.
- Frequency: How often a customer makes a purchase.
- Monetary: How much money a customer spends.
Other features like customer demographics, product categories, and engagement metrics are also created.
## Exploratory Data Analysis (EDA)
EDA involves analyzing the data to summarize its main characteristics, often using visualizations. This step helps in understanding the data distribution, identifying patterns, and uncovering insights that can guide the modeling process.
## PowerBI Dashboard
A PowerBI dashboard is created to visualize the data, model predictions, and insights. This interactive dashboard allows stakeholders to explore the data and gain a deeper understanding of customer behavior and CLV predictions.
## Model Training and Prediction
The project uses linear regression to predict CLV. The steps involved include:
- Splitting the data into training and testing sets.
- Training the linear regression model on the training set.
- Evaluating the model on the testing set using metrics like Root Mean Squared Error.
- Making predictions on new data.
