# Project Name

Surprise Housing - Lasso and Ridge Regression


## Table of Contents
* [General Info](#general-information)
* [Business Goal](#Business-Goal)
* [Regularization](#Regularization)
* [Conclusions](#conclusions)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing decided to enter the Australian market.The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. The company is looking at prospective properties to enter the market. To build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

- Which variables are significant in predicting the price of a house

- How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Business Goal
To model the price of houses with the available independent variables which is used by the management to understand how exactly the prices vary with the variables. Accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Regularization
- All the relationship between independent and target variable is identified and studied. The outlier treatment is done for required column.
- The Dummy variables for the categorical variables are created along with test and train data.
- The Best Parameter(alpha) of Lasso and Ridge Regression is identified. Also tested with the test data

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Conclusions
The Alpha of Lasso and Rige is 0.001 and 6
The important features of Lasso are GrLivArea,OverallQual_9,OverallQual_8,KitchenAbvGr_1,Neighborhood_Crawfor
The important features of Ridge are GrLivArea,OverallQual_9,OverallQual_8,Neighborhood_Crawfor,OverallCond_9





<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->