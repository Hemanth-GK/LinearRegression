# Project Name
> Linear Regression performed on the Boombikes bike rental dataset as part of an assignment for coursework in the course Executive PG in Machine Learning and AI from IIIT Bangalore.

## Table of Contents
General Information
Technologies Used
Conclusions

## General Information
Multiple linear regression is performed on the dataset.
The project is done as part of coursework in the Machine Learning module.
We are trying to find the number of rentals issued from the company based on numerous independent values such as temperature, weather, humidity, holiday, etc.
The Boombikes bike rental dataset is being used.

## Conclusions
TThe top 5 variables that are seen effecting and benefitting the Bike Rental count are as follows:

spring : -0.4662 month_Sep : 0.2079 temp : 0.4196 Light Snow : -1.2970 weekday_Mon : 0.1586

Our developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.

The major steps included in the python notebook are data interpretation, data visualisation, data pre-processing, model training, feature selection, residual analysis, model evaluation on the test set.

Concepts such as EDA, p-value, VIF, RFE were used and model building was done using statsmodels library

## Technologies Used
pandas
seaborn
matplotlib
statsmodels
sci-kit learn
numpy

## Contact
Created by [@Hemanth-GK] - feel free to contact me!
