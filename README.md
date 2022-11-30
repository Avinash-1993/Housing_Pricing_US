# House-Price-Prediction IIITB November 2022
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Inference](#inference)
* [Contact](#contact)


## General Information
- The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.
- You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market. Ridge and Lasso Regeression
- The company wants to know:
  Which variables are significant in predicting the price of a house, and
  How well those variables describe the price of a house.
  Also, determine the optimal value of lambda for ridge and lasso regression.

## Technologies Used
- matplotlib          
- numpy               
- pandas              
- seaborn             
- sklearn             
- statsmodels         
- warnings

## Conclusions
These are the final features that should be selected for predicting the price of house
Hence the equation:
Log(Y) = C + 0.125(x1) + 0.112(x2) + 0.050(x3) + 0.042(x4) + 0.035(x5) + 0.034(x6) + 0.024(x7) + 0.015(x8) + 0.014(x9) + 0.010(x10)+ 0.010(x11) + 0.005(x12) - 0.007(x13) - 0.007(x14) - 0.008(x15) - 0.095(x16) + Error term(RSS + alpha * (sum of absolute value of coefficients)

## Inference
Suggestions for Surprise Housing is to keep a check on these predictors affecting the price of the house.
The higher values of positive coeeficients suggest a high sale value.
Some of those features are:-
GrLivArea
OverallQual
OverallCond
TotalBsmtSF
GarageArea
The higher values of negative coeeficients suggest a decrease in sale value.
Some of those features are:-
PropAge
MSSubClass
When the market value of the property is lower than the Predicted Sale Price, its the time to buy.

## Contact
Created by [@Avinash-1993] - feel free to contact me!