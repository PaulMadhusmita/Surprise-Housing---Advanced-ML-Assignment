# Project Name
> The company Surprise Housing is looking at prospective properties to buy to enter the market. Objective is to build a regression model using regularisation in order to predict the actual value of the prospective properties and help them decide whether to invest in them or not.

The company wants to know:

 * Which variables are significant in predicting the price of a house, and

 * How well those variables describe the price of a house.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information

Model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables.

The company Surprise Housing has collected a data set from the sale of houses in Australia. They wish to use data analytics to purchase houses at a price below their actual values and flip them on at a higher price
Build a regression model using regularisation in order to predict the actual value of the prospective properties. 
Also, determine the optimal value of lambda for ridge and lasso regression.

The data dictionary to understand the variables is present in below path:
https://cdn.upgrad.com/UpGrad/temp/87f67e28-c47e-4725-ae3c-111142c7eaba/data_description.txt

## Conclusions

R2 Score both Ridge and Lasso regression.
Ridge : Train :92.9 Test :89.7
Lasso : Train :94.3 Test :90.0

Top 5 most significant variables in Ridge are:
YearBuilt
OverallCond
BsmtFinSF1
MSSubClass
BsmtUnfSF

Top 5 most significant variables in Lasso are:
YearBuilt
MasVnrArea
MSSubClass
OverallCond
BsmtFinSF2

Optimal Value of Lambda:
Ridge : 10
Lasso : 0.001
Since, we have a huge number of predictors, hence Lasso model is more appropriate in this case as it helps in eliminating features by pushing model coefficients towards 0

## Technologies Used
Python : 3.0

## Libraries Used
Numpy 1.20.3
Pandas  1.3.4
matplotlib.pyplot
seaborn 0.11.2
sklearn  0.24.2


## Acknowledgements

- This project was inspired by Upgrad AI/ML course assignment

## Contact
Created by [@PaulMadhusmita] - feel free to contact me!

