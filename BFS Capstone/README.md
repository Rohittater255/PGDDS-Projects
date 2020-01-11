# BFS Capstone Project -Bank Marketing

## Business Understanding
CredX is a leading credit card provider that gets thousands of credit card applications every year. But in the past few years, it has experienced an increase in credit loss. The CEO believes that the best strategy to mitigate credit risk is to ‘acquire the right customers’.

In this project, your task is to help CredX identify the right customers using predictive models. Using past data of the bank’s applicants, you need to determine the factors affecting credit risk, create strategies to mitigate the acquisition risk and assess the financial benefit of your project.   

## Understanding the data
There are two data sets in this project: demographic and credit bureau data.  

Demographic/application data: This is obtained from the information provided by the applicants at the time of credit card application. It contains customer-level information on age, gender, income, marital status, etc.
Credit bureau: This is taken from the credit bureau and contains variables such as 'number of times 30 DPD or worse in last 3/6/12 months', 'outstanding balance', 'number of trades', etc.

## Libraries Used
Sklearn
Matplotlib & Seaborn
Numpy & pandas

## Models Build
1. Logistic Regression
2. Random Forest
3. Decision Trees

## Steps Performed
Part 1 - Importing Libraries & Creating UDF -  
 -	Impoting Libraries       
 -	Creating User Defined Functions              

Part 2 - Building Model on Demographic Data -   -
 - i. Data Importing & Data Understanding  
 - ii. Data Cleaning   
 - iii. Exploratory Data Analysis
 - iv. Model Buiding on Non WOE Dataset
 	- Data Preparation
	- Test Train Split
	- Standardization
	- Model Building
 - v. Model Buiding on Woe Dataset   
 	 - Calculate WOE & IV
	 - Create WOE Dataframe   
	 - Test Train Split   
	 - Model Building

Part 3 - Building Model on Demographic Data + Credit Data -  
 - i. Data Importing & Data Understanding  
 - ii. Data Cleaning   
 - iii. Exploratory Data Analysis
 - iv. Model Buiding on Non WOE Dataset
 	- Data Preparation
	- Test Train Split
	- Standardization
	- Model Building
 - v. Model Buiding on Woe Dataset   
 	 - Calculate WOE & IV
	 - Create WOE Dataframe   
	 - Test Train Split   
	 - Model Building

Part 4 - Model Selection & Model Evaluation -
 - i. Selection of Best Model
 - ii. Model Evaluation
 - iii. Application Scorecard
 - iv. Assessing the financial benefit of Model
 
## Selection of Best Model
FINAL SELECTED MODEL - `LOGISTIC REGRESSION ON WOE DATASET`



Reasons for selection of this model:
 - Our Business Objective is acquire the right customers, hence we should select model with good Sensitivity & Specificity value
 - From above summary table we can see that, the model having good sensitivity & specificity is Logistic Regression model built on WOE
Dataset.
 - Hence we are selecting Logistic Regression model build on WOE Dataset as our final model.
 
## Key Findings
Top Predictors obtained from Logistic Model are - 
 - 30DPD_6Months
 - Avgas_Utilization_12Months
 - Trades_12Months
 - Enquires_6Months
 - Age
 
 ## Assessing the financial benefit of selected Model
 - The model can detect 75% of defaulters by targeting 50% applicants.
 - The model can detect 62% of defaulters.

