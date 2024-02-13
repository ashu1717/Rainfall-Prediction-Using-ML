# Rainfall-Prediction-Using-ML

## Overview

This project focuses on creating a machine learning model to predict rainfall in Sydney. The project is undertaken for "The Daily Buzz," a newspaper company, to enhance the accuracy of their weather predictions and provide a valuable service to their readers.

## Dataset

The dataset used for this project contains weather information in Sydney from 2008 to 2017. It includes the following columns:

- **Date**: The date of observation
- **Location**: The common name of the weather station
- **MinTemp**: The minimum temperature in degrees Celsius
- **MaxTemp**: The maximum temperature in degrees Celsius
- **Rainfall**: The amount of rainfall recorded for the day in mm
- **Evaporation**: The Class A pan evaporation (mm) in the 24 hours to 9 am
- **Sunshine**: The number of hours of bright sunshine in the day
- **Humidity 9am**: Humidity (percent) at 9 am
- **Humidity3pm**: Humidity (percent) at 3 pm
- **Pressure 9am**: Atmospheric pressure (hPa) reduced to mean sea level at 9 am
- **Pressure 3pm**: Atmospheric pressure (hPa) reduced to mean sea level at 3 pm
- **Cloud 9 am**: Fraction of sky obscured by cloud at 9 am (measured in "oktas")
- **Cloud 3 pm**: Fraction of sky obscured by clouds at 3 pm (in "oktas")
- **Temp 9 am**: Temperature (degrees C) at 9 am
- **Temp 3 pm**: Temperature (degrees C) at 3 pm
- **RainToday**: Boolean (1 if precipitation in the 24 hours to 9 am exceeds 1 mm, otherwise 0)
- **RainTomorrow**: Boolean (next day rain)

## Approach

### Data Preprocessing

- Load and explore the dataset.
- Handle missing values, encode categorical variables, and perform data scaling.
- Split the data into training and testing sets.

### Model Building and Evaluation

- Implement a Decision Tree Classifier as the baseline model.
- Evaluate the Decision Tree model using accuracy and create a confusion matrix.
- Implement ensemble methods, including Random Forest and Gradient Boosting.
- Compare the performance of these models using various metrics.

### Analysis and Documentation

- Explain each step of the analysis in the Jupyter Notebook.
- Visualize results and model performance using plots and graphs.
- Discuss why a particular model is selected as the best performer based on evaluation metrics.
- Suggest ways to further improve the selected model's accuracy.

## Available Machine Learning Models

The models used in this project include:

- Decision Trees
- Random Forest
- Gradient Boosting

These models are chosen for their suitability in classification tasks.
