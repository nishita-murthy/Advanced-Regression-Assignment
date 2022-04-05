# Advanced-Regression-Assignment

## Problem Statement

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. <br/>
The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.


The company wants to know:

* Which variables are significant in predicting the price of a house, and
* How well those variables describe the price of a house.

Below are the steps followed through the code file:
    
* Step 1: Importing, reading and understanding the data
* Step 2: Data cleaning 
* Step 3: Analyzing the predictor variables with the response variable (univariate and bivariate)
* Step 4: Recursive Feature Elimination (RFE)
* Step 5: Ridge and Lasso Regression


## Conclusion

Below are the final alpha values for both the models:

* **Ridge**: alpha = 10
* **Lasso**: alpha = 0.001

Among the 2 models (Ridge and Lasso) considering the Mean Square Error values and R-squared values, we can conclude that the regression performed using the Ridge model has better results than Lasso.
