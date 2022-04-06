# Predicting Housing Prices in Australia
> Surprise Housing is looking to invest in the Australian market, but being new to Australia, does not know which variables are significant in predicting the price of a house, and how well those variables describe the price of a house.


## Table of Contents
* [0. Business Problem](#0-business-problem)
* [1. Data Understanding](#1-data-understanding)
* [2. Data Cleaning](#2-data-cleaning)
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
- This project aims to help a US-based housing company named Surprise Housing that has decided to enter the Australian market. The company is looking at prospective properties to buy to enter the market; therefore, our aim is to build a regression model using regularisation in order to predict the actual value of the prospective properties and help the company understand which variables are significant in predicting the price of a house, and how well those variables describe the price of a house.

## Conclusions
The three features that contribute strongly to the model are.
1. Year. This means that year is a important feature because more bikes are rented out during the second year (2019) when the company became more established and well-known in USA.
2. Not Spring. When the season is not spring, more bikes are rented out as Spring is a season when temperatures are lower and snow and dangerous weather conditions are more frequent. Note that this feature was featured engineered and not from the original dataset. 
3. Weather is not snow. When the weather is snowing, far fewer bikes are rented out as it is safer to ride, and there is a strong inverse relationshp, as indicated by high negative beta coefficient value. Note that this feature was featured engineered and not from the original dataset. 

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