# House Price Prediction with Advanced Regression

This Code will help you predict House price with help of Advanced Regression


## Problem Statement
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market.

You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:
 - Which variables are significant in predicting the price of a house, and
 - How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

## Business Goal 

You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for the management to understand the pricing dynamics of a new market.
You are required to model the price of cars with the available independent variables. It will be used by the management to understand how exactly the prices vary with the independent variables. They can accordingly manipulate the design of the cars, the business strategy etc. to meet certain price levels. Further, the model will be a good way for management to understand the pricing dynamics of a new market. 

## Data Description
There is a variable named CarName which is comprised of two parts - the first word is the name of 'car company' and the second is the 'car model'. For example, chevrolet impala has 'chevrolet' as the car company name and 'impala' as the car model name. You need to consider only company name as the independent variable for model building. 

## Libraries Used
 - sklearn
 - matplotlib
 - numpy
 - pandas
 - matplotlib
 - seaborn

## Steps Performed
 - Reading and Understanding the Data
 - Data Analysis
 - Data Preparation
 - Scaling the features
 - Splitting the Data into Training and Testing Sets
 - Model Building
 - Model Evaluation
 - Result Analysis


## Final Model
The final R2_score of the model is 0.87

## Important Variables
The variables are significant in predicting the price of a car are:-

 - Enginesize (Size of Engine)
 - Company_bmw(Cars manufactured by BMW)
 - Enginelocation_rear(Cars having enginelocation as rear )
 - Enginetype_rotor(Cars having enginetype as rotor)
 - Carheight(Height of car)
