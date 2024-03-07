# Bike Sharing Prediction

## Introduction
This data science project focuses on analyzing and predicting bike sharing demand in Seoul. The primary objective is to enhance the understanding of bike rental patterns and contribute valuable insights for optimizing the bike-sharing system in the city.

## Objectives
1. Exploratory Data Analysis (EDA): Conducted an in-depth analysis of the dataset, exploring relationships among various features, and addressing data preprocessing tasks. Explored both categorical and numerical variables, identifying correlations, distributions, and connections to the dependent variable, "Rental Bike Count."
2. Modeling: Explored a range of individual models, from Linear Regression to more advanced ensemble models like Random Forest, Gradient Boost, and Light GBM. The goal was to identify a model that accurately predicts bike rental counts.
3. Hyperparameter Tuning: Optimized the model's performance through hyperparameter tuning to ensure better predictions and prevent overfitting.

## Methodology
* Data Exploration: Explored the dataset, including analysis of rental patterns, hourly trends, and correlations with weather conditions.
* Feature Engineering: Preprocessed the data by encoding categorical variables, handling multicollinearity, and removing unnecessary features identified during EDA.
* Model Selection: Evaluated various models and selected Light GBM as the final model based on its superior performance in predicting rented_bike_count.

## Results
* Achieved a training R2 score of around 99% and a test R2 score of 95.8% using the selected Light GBM model. The results indicate the model's effectiveness in capturing bike rental patterns.
* Key Findings:
  1. Identified two distinct rental patterns based on working and non-working days.
  2. Highlighted the impact of variables such as temperature, season, weather, and humidity on bike rental counts.
  3. Chose Light GBM as the preferred model for its superior performance in predicting rental counts.
* Limitations:
  1. Acknowledged the time-dependent nature of the data, with certain variables subject to variations over time.
  2. Recognized the need for continuous monitoring and potential retraining of the model as more data becomes available.
     
## Conclusion
In conclusion, this project provides valuable insights into managing bike-sharing demand in Seoul. The analysis suggests practical solutions for optimizing bike station locations, considering peak rental hours, and efficient maintenance scheduling. The selected Light GBM model demonstrates strong predictive capabilities, with the potential for further improvement with additional data. The project's findings contribute to the ongoing evolution of the field, emphasizing the importance of staying informed in the rapidly advancing domain of machine learning.
