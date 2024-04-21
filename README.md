# Linear-Regression-Analysis-for-Automobile-Price-Prediction

# Overview
This project aims to predict car prices using linear regression. The dataset contains information about various car attributes such as make, model, year, mileage, fuel type, and price. We will perform data cleaning and preprocessing before training a linear regression model to predict car prices accurately.

# Data Cleaning
Loading Data: Load the dataset from the CSV file quikr_car.csv using Pandas. Initial Inspection: Display the first few rows of the dataset to understand its structure and contents. Handling Missing Values: Identify and handle missing values in the dataset. Correcting Data Types: Convert columns like 'year', 'price', and 'kms_driven' to the appropriate data types. Cleaning 'Price' Column: Remove rows with 'Ask For Price' and convert the 'price' column to integers. Cleaning 'kms_driven' Column: Convert the 'kms_driven' column to integers after removing commas. Standardizing Company Names: Extract the first three words of the 'name' column to standardize company names.

# Model Training
Data Preparation: Split the dataset into features (X) and target variable (y). Encode categorical features using One-Hot Encoding. Splitting Data: Split the dataset into training and testing sets using train-test split. Model Initialization: Initialize a Linear Regression model. Pipeline Creation: Create a pipeline including One-Hot Encoding and Linear Regression. Model Training: Fit the pipeline to the training data. Model Evaluation: Evaluate the model's performance using the R-squared score.

# Hyperparameter Tuning
Maximizing R-squared Score: Run a loop to find the maximum R-squared score by training the model multiple times with different random states.
