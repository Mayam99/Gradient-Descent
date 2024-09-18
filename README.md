Car Prices Prediction Using Linear Regression

This repository contains the implementation of a Linear Regression model to predict car prices based on various features from the Car Prices Prediction Dataset. The project aims to develop a predictive model using Gradient Descent and analyze how different attributes such as Make, Model, Year, Mileage, and Condition influence the price of a car.

Dataset Overview

The dataset includes the following features:

* Make: The car manufacturer (e.g., Toyota, Ford).
* Model: The specific car model (e.g., Accord, Corolla).
* Year: The year the car was manufactured.
* Mileage: The total mileage (in kilometers or miles).
* Condition: The overall condition of the car.
* Price: The target variable representing the car's price.

Project Objective

The main objective is to develop a regression model that can accurately predict car prices using the available features. This project focuses on:

1) Data Preprocessing: Cleaning, encoding categorical variables, and scaling numerical features.
2) Model Development: Implementing linear regression with Gradient Descent to find the optimal weights for predicting car prices.
3) Model Evaluation: Using performance metrics such as Mean Squared Error (MSE) and R-squared to evaluate the model.
4) Visualization: Visualizing relationships between features and target variables, and plotting the best-fit line for selected features.

Key Features of the Repository

* Exploratory Data Analysis (EDA): A thorough analysis of feature distributions and their relationships with the target variable.
* Gradient Descent Algorithm: Custom implementation of the gradient descent algorithm for linear regression.
* Model Performance Evaluation: Code to evaluate the regression model and display results in a meaningful way.
* Visualization: Includes plots of the best-fit line for univariate linear regression and scatter plots of key feature correlations.

Technologies Used

* Python: Core programming language for the analysis.
* Pandas: For data manipulation and analysis.
* NumPy: For mathematical operations and array handling.
* Matplotlib: For data visualization.
* Scikit-learn: For data preprocessing and model evaluation metrics.
