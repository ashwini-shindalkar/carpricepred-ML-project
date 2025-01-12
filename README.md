# Car Price Prediction with Machine Learning.

**Team members**

- individual.


## Problem Statement

**Project Overview:**

This is an Automobile Imports Data set Which contains various characteristics of the cars including insurance risk rating and other price indicators. The target is to predict the price of the cars.

**Key Objectives:**

- Task 1:-Prepare a complete data analysis report on the given data.

- Task 2:-Create a predictive model by applying some data science techniques for the price of cars with the available independent variables. That should help the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels.
---

## Project Summary

**Objective:** Develop a machine learning model to predict car prices based on various influencing factors.

**Why Car Price Prediction?** Car prices are influenced by numerous variables, including brand reputation, features, horsepower, and fuel efficiency. Machine learning models can provide accurate price predictions.

**Key Tasks:**

1. **Data Collection:** Gather data on various car attributes and their corresponding prices.
2. **Data Preprocessing:** Clean, transform, and prepare the data for modeling.
3. **Feature Engineering:** Identify the most important features for price prediction.
4. **Model Building:** Create a machine learning model capable of predicting car prices.
5. **Model Evaluation:** Assess the model's accuracy and performance using appropriate metrics.
6. **Deployment:** Make the trained model available for car price predictions.

**Benefits:** By completing this project, we'll gain valuable insights into machine learning, data analysis, and the automotive industry. We'll also have a functional car price prediction model that can be useful for future car pricing decisions.

---

## Results

I have selected R2 score as the primary evaluation metric for the Car Price Prediction model. And after removing the overfitted models which have MSE, R2 score, Adjusted R2 score for train as 100% and also have negative accuracy value, we get the final list:

| Sl. No. | Regression Model      |   R2 Train (%) |   R2 Test (%) |
|:--------|:--------------------------|---------------:|--------------:|
|    1    | Lasso Regression        |       0.71|      0.70 |
|    2    | Lasso Regression tuned       |       0.91 |      0.86 |
|    3    | Linear Regression |       0.92|      0.84|
|    4    | Linear Regression tuned       |       0.92 |      0.84|
|    5    | Dicision tree tuned       |       0.98|      0.61 |
|    6    | Random forest        |       0.96 |      0.71|
|    7    | Random Forest tuned             |       0.96 |      0.72 |
|    8    | XGBoosting Regressor tuned        |       0.97 |      0.74 |


## Conclusion

This project explores the automotive industry's intricate dynamics, aiming to predict car prices with machine learning. By analyzing various factors such as fuel type, seller type, and transmission, we uncover valuable insights and select a robust model for accurate price prediction.

**Key Insights:**

The number of cars having their 'Fuel_Type' type as gas is greater then compared to the diesel
A higher proportion of "std" vehicles might suggest that the market is currently trending towords simple,r more affordable vehicles
Various machine learning models were assessed, with the Lasso model being chosen for car price prediction due to its robust performance.
The project used the R2 score as the primary evaluation metric to assess model accuracy.
The Lasso model achieved impressive accuracy with 91% training accuracy and 86% testing accuracy, making it a suitable choice for car price prediction.
The insights provide a holistic understanding of the factors influencing car prices, both from exploratory data analysis and machine learning model perspectives. The Lasso regression model's accuracy underscores its potential for practical applications in the automotive market.

This project has not only equipped us with valuable data science skills but has also deepened our understanding of car pricing, making it a significant step in the field of data science and machine learning.

Thank you!!