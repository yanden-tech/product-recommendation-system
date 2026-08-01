# Building Product Recommendation Systems Using Real-World Retail and Gaming Data

An end-to-end data science project that leverages Amazon Product Reviews, Steam user interactions, and Video Game Sales data to build machine learning models and uncover the factors driving customer engagement and product success.


## Project Overview

This project develops an end-to-end data science pipeline using real-world e-commerce and gaming datasets. It includes data quality assessment, data preprocessing, exploratory data analysis (EDA), feature engineering, predictive modeling, and model evaluation.

The objective is to transform raw data into actionable insights and demonstrate how machine learning can identify the factors associated with product success and user engagement.

The project was adapted from a general e-commerce recommendation framework to focus on predictive analytics in the gaming industry. By integrating Steam user engagement data, Amazon review information, and Global Video Game Sales data, this project investigates the signals that influence commercial performance and user engagement.


## Datasets

- Amazon Product Reviews
- Steam User Interactions
- Global Video Game Sales

## Machine Learning Models

The following regression models were evaluated:

- Random Forest
- Hist Gradient Boosting
- Ridge Regression
- Lasso Regression
- Elastic Net

## Project Workflow

1. Data Quality Assessment
2. Data Preprocessing
3. Exploratory Data Analysis
4. Feature Engineering
5. Multi-source Data Integration
6. Predictive Modeling
7. Model Evaluation


## Key Results

- Random Forest achieved the highest predictive performance among the evaluated regression models.
- Steam engagement variables, particularly playtime and user activity signals, were the strongest predictors of Global Video Game Sales.
- Amazon review ratings contributed limited predictive value due to low overlap between Amazon product records and the video game datasets.
- The results suggest that player engagement signals are more strongly associated with commercial success than sparse external review sentiment data.

## Author
Yande Ndiaye
