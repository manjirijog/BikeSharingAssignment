# Bike Sharing Assignment
> This is a programming assignment wherein a multiple linear regression model is to be built for the prediction of demand for shared bikes.


## Table of Contents
* [Background](#Background)
* [Problem Statement](#Problem-Statement)
* [General information about the data](#General-information-about-the-data)
* [Technologies used](#Technologies-used)
* [Conclusions](#Conclusions)

<!-- You can include any other section that is pertinent to your problem -->
## Background

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Problem Statement
- For a US bike-sharing provider company BoomBikes, understand the factors on which the demand for these shared bikes depends. More specifically, to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## General information about the data
- Given information about the data: Data is captured in a csv file named day.csv 
- Variables like 'weathersit' and 'season' have values as 1, 2, 3, 4 which have specific labels associated with them - Read from Data dictionary. 
- Column 'yr' with two values 0 and 1 indicating the years 2018 and 2019 respectively. 
- The variable 'casual' = the number casual users who have made a rental The variable 'registered' = total number of registered users who have made a booking on a given day. The variable 'cnt' = total number of bike rentals, including both casual and registered. 
- The model should be built taking this 'cnt' as the target variable

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Technologies used
- Python

## Conclusions
- A Multiple Linear Regression model is built.
- Predictions on Train and Test data are very close, which means the model is well-behaved and is not By Chance.
- Approximately 77% of the variance is explained by the significant independent variables used to build the model.
- Significant variables to predict the demand for bike rentals are:
'year', 'holiday', 'temperature', 'windspeed', 'Season' ('Spring', 'Winter'), 'month' ('july'), and 
'weathersit' ('Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist'), '(Clear, Few clouds, Partly cloudy, Partly cloudy)'.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->