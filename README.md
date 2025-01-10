# Predicting-Employee-Salary-Using-Regression-Models-A-Comparative-Study
In this project, we performed Salary Prediction using Regression Analysis. Two models, Linear Regression and Random Forest, were analyzed. The Random Forest model was executed in R software. Upon comparison, Linear Regression outperformed Random Forest in predicting salary more accurately, showing better MSE.
Key Objectives: The primary objective of this project was to develop a predictive model for forecasting salary based on key features such as Age, Gender, Education Level, and Years of Experience. To achieve this, we employed two distinct regression models — Linear Regression and Random Forest — and compared their performance to determine the most effective model for accurate salary prediction.

**Data Overview:**
The dataset used for this analysis contains employee attributes such as Age, Gender, Education Level, Years of Experience, and Salary. Among these, Gender and Education Level are categorical variables, while Age and Years of Experience are continuous. The target variable in this project was Salary, which we sought to predict based on the other input features.

**Approach:**
1. Linear Regression Analysis:
In the initial phase, we performed Linear Regression to evaluate the linear relationship between the independent variables (Age, Gender, Education Level, Years of Experience) and the target variable (Salary). The model was built to find the best-fit line and provide predictions based on this relationship.

2. Random Forest Analysis:
For the second phase, we applied Random Forest, a non-linear machine learning technique, to the same dataset. Random Forest, performed using R software, is an ensemble learning method that constructs multiple decision trees and aggregates their outputs to make more accurate predictions.

**Model Comparison:**
After fitting both models to the dataset, we compared their performances using Mean Squared Error (MSE) and R-squared (R²) values. The analysis revealed that while Random Forest is a powerful model capable of capturing complex relationships, Linear Regression yielded a lower MSE and higher R² value, making it a more suitable model for this specific dataset.

**Expected Outcomes:**
The key expectation from this project was to evaluate which regression model, between Linear Regression and Random Forest, provided more accurate predictions of salary. The outcomes were anticipated to offer insights into the suitability of linear vs. non-linear models for this type of predictive task.

**Conclusion:** 
Upon completing the analysis, it was concluded that Linear Regression was the better performing model for predicting salary in this case, with a lower MSE and higher R² value compared to Random Forest. Although Random Forest offers the advantage of handling non-linear relationships, it did not outperform Linear Regression in this specific dataset. This project highlights the importance of model selection based on the nature of the data and the specific problem at hand.
