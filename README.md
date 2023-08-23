## Advanced Regression
This assignment is a programming assignment wherein you have to build a advanced regression model for the prediction of house pricing

## Table of Contents
* [Problem Statement](#problem-statement)
* [Objective](#objective)
* [Steps Followed](#steps-followed)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)

## Problem Statement:
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price.The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

## Objective
- Which variables are significant in predicting the price of a house
- How well those variables describe the price of a house.
- Also, determine the optimal value of lambda for ridge and lasso regression.

## Steps followed
- Importing and comprehending data.
- Value reduction and outlier analysis
- Exploratory data analysis is used to draw conclusions about the data and its -   relationship to the goal variables.-
- The target variable is transformed to account for data skewness.
- Data preprocessing techniques include label encoding and dummy creation.
- Feature scaling and test train splitting
- Ridge and Lasso Regression are used to identify the most important feature variables and the best alpha value.

## Conclusions
    The following variables are significant in forecasting property prices: -
    - GrLivArea
    - OverallQual_9
    - OverallCond_9
    - OverallQual_8
    - Neighborhood_Crawfor
    - Functional_Typ
    - Exterior1st_BrkFace
    - SaleCondition_Alloca
    - CentralAir_Y
    - TotalBsmtSF
    - Neighborhood_Somerst
    - TotalBsmtSF and
    - Condition1_Norm


    How well those variables describe the price of a house?
    Here will see only top few variables:-

    - GrLivArea: For every additional square foot of dwelling area above ground, the price will rise by 1.09 to 1.11 times.
    - OverallQual_9 & OverallQual_8: If the house's overall material and finish are very Good or Excellent, the price will increase by 1.08 to 1.13 times.
    - Neighborhood_Crawfor: If Crawford is nearby, the house price will rise by 1.07 to 1.09 times.
    - Functional_Typ: If the home functionality is usual, the price of the house will increase by 1.07 to 1.08 times.
    - Exterior1st_BrkFace: If the house's exterior covering is Brick Face, the price will increase by 1.07 to 1.08 times.
    - Similarly, we can determine how well each variable describes the price of a house.
        Optimal value of lambda for Ridge Regression = 10
        Optimal value of lambda for Lasso = 0.001

## Technologies Used
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- sklearn
- statsmodel

## Acknowledgements
- This project was inspired by Upgrad MS course for ML and AI
- This project was based on [this course](https://www.upgrad.com/masters-in-ml-ai-ljmu/).


## Contact
Created by [@akshayvmkadam] - feel free to contact me!