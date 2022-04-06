# Predicting Housing Prices in Australia
> Surprise Housing is looking to invest in the Australian market, but being new to Australia, does not know which variables are significant in predicting the price of a house, and how well those variables describe the price of a house.


## Table of Contents
* [0. Business Problem](#0-business-problem)
* [1. Data Understanding](#1-data-understanding)
* [2. Data Cleaning](#2-data-cleaning)
    * [2.1 Data Cleaning](#21-data-cleaning)
    * [2.1 Feature Engineering](#22-feature-engineering)
* [3. Data Analysis](#3-data-analysis)
    * [3.1 Categorical Variables](#31-categorical-variables)
    * [3.2 Numerical Variables](#32-numerical-variables)
    * [3.3 Summary](#33-summary)
* [4. Model Building](#4-model-building)
    * [4.1 Multiple Regression](#41-multiple-regression)
    * [4.2 Ridge Regression](#42-ridge-regression)
    * [4.3 Lasso Regression](#43-lasso-regression)
    * [4.4 Summary](#44-summary)
* [5. Model Evaluation](#5-model-evaluation)

## General Information
### Business Problem
-  This project aims to help a US-based housing company named Surprise Housing that has decided to enter the Australian market. The company is looking at prospective properties to buy to enter the market; therefore, our aim is to build a regression model using regularisation in order to predict the actual value of the prospective properties and help the company understand which variables are significant in predicting the price of a house, and how well those variables describe the price of a house.

### Project Objective
- Dicover which variables are significant in predicting the price of a house, and how well those variables describe the price of a house.

## Conclusions
1. Chose a Lasso Regression because Lasso Regression performs RFE, which will be useful to reduce the large number of feature columns, as many of the feature columns do not contribute to the dependent variable or are highly correlated, and they have to be eliminated.
2. Neighborhood feature columns is a feature column that can strongly predict housing prices when one-hot-encoded. Some neighborhood areas correlate strongly to the housing prices, such as NridgHt,StoneBr and NoRidge.	Another column which correlates is HouseStyle,in particular 2Story.
3. Continous, numeric featuers such as ExterQual and 2ndFlrSF were also found to have correlated strongly.


## Technologies Used
python:  3.8.8
numpy:  1.19.5
pandas:  1.2.4
matplotlib:  3.3.4
seaborn:  0.11.1
plotly:  5.5.0
statsmodels:  0.12.2
sklearn:  0.24.1

## Contact
Created by [@bengcheo] - feel free to contact me!
