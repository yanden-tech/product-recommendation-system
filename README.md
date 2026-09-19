# Building Product Recommendation Systems Using Real-World Retail and Gaming Data

An end-to-end data science project that leverages Amazon Product Reviews, Steam user interactions, and Video Game Sales data to analyze customer engagement patterns, build predictive machine learning models, and identify the factors associated with product success.


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


## Results & Impact

- Random Forest achieved the strongest regression performance for the Steam and Global Sales datasets, while Ridge performed best for Amazon review-rating prediction.

- Global Video Game Sales showed meaningful predictive relationships with game characteristics and user engagement signals, although substantial variation remained unexplained.

- In the integrated Master Dataset, user engagement signals such as helpful and funny review interactions and playtime showed relatively high predictive importance for Global Sales.

- Amazon review ratings provided limited predictive value, partly reflecting the limited overlap between Amazon product records and gaming sales data.

- The analysis highlights the potential value of behavioral engagement signals when analyzing commercial outcomes across gaming and review data.
 

## Author
Yande Ndiaye
