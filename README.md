# House-Price-Prediction-Case-Study

> This assignment is a programming assignment wherein you have to build a multiple linear regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
- What is the background of your project?

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. 

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

  - Which variables are significant in predicting the price of a house, and
  - How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

- What is the business problem that your project is trying to solve?

A model needs to be built to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

- What is the dataset that is being used?

Dataset names train.csv is used. The dataset contains 1460 rows and 81 columns.

## Conclusions

## Conclusion :

- The optimal lambda value in case of Ridge and Lasso is as below:
    - Ridge - 10
    - Lasso - 0.0004
    
- The Mean Squared error in case of Ridge and Lasso are:
    - Ridge - 0.01361
    - Lasso - 0.01332

- The Mean Squared Error of Lasso is slightly lower than that of Ridge

- Also, since Lasso helps in feature reduction (as the coefficient value of one of the feature became 0), Lasso has a better edge over Ridge.
  
- Hence based on Lasso, the factors that generally affect the price are the Zoning classification, Living area square feet, Overall quality and condition of the house, Foundation type of the house, Number of cars that can be accomodated in the garage, Total basement area in square feet and the Basement finished square feet area 
    
Therefore, the variables predicted by Lasso in the above bar chart as significant variables for predicting the price of a house.

## Technologies Used

- jupyter_client - 7.3.5
- matplotlib - 3.5.3
- numpy - 1.23.2
- pandas - 1.4.4
- seaborn - 0.11.2
- statsmodels -0.11.1
- scikit-learn 1.1.2  


## Contact
Created by [puspanjalis](https://github.com/puspanjalis) - feel free to contact me!
