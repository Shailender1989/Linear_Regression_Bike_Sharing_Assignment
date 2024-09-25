# To Build “Bike Sharing” Linear regression Model 
>Problem Statement:
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
>Business Objective :
We are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Table of Contents
* Overview of business objective
* Reading and understanding the given dataset.
* Cleaning the data and perform EDA
* Visualizing the Data.
* Data preparation.
* Split the data as training and test sets.
* Model building
* Model evaluation.
* Conclusions / Comparisons.

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Performed analysis on day.csv dataset.


## Conclusions drawn after evaluating the model
- Train dataset R^2          : 0.779
- Test dataset R^2           : 0.7417
- Train dataset Adjusted R^2 : 0.774    
- Test dataset Adjusted R^2  : 0.7281

## Technologies Used
- library 
- import numpy as np
- import pandas as pd
- import matplotlib.pyplot as plt
- import seaborn as sns
- from sklearn.model_selection import train_test_splitfrom sklearn.preprocessing import MinMaxScaler
- from sklearn.feature_selection import RFE
- from sklearn.linear_model import LinearRegression
- from statsmodels.stats.outliers_influence import variance_inflation_factor
- import statsmodels.api as sm
- from sklearn.metrics import r2_score
- Jupiter Notebook  
- Python version - Python 3.11.7

## Acknowledgements
My sincere thanks to upgrad and IIIT Banglore professors for teaching the concepts and making us perform the assignments.


## Contact
Created by [@Shailender1989] - feel free to contact me!
