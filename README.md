# Task3
Linear Regression Task
ask 3: Linear Regression
This repository contains the solution for Task 3 of the Elevate Labs AI & ML Internship, which focuses on implementing and understanding simple and multiple linear regression.
Objective
The primary objective was to implement linear regression models using Python and scikit-learn. The task required a clear understanding of the full machine learning workflow, from data preparation and model training to evaluation and interpretation of the results
Tools Used:
-Python: The main programming language used.
-Pandas: Utilized for data handling and preprocessing.
-Scikit-learn: A core library used to split the data, fit the linear regression model, and calculate evaluation metrics.
-Matplotlib: Employed for visualizing the results and plotting the regression line.
Dataset:
Dataset Name: House Price Prediction Dataset
Source: https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction
Implementation Steps
Data Import and Preprocessing: The dataset was imported using pandas, and any necessary data cleaning or feature selection was performed.
Data Splitting: The data was split into training and testing sets to ensure the model could be evaluated on unseen data.
Model Training: A LinearRegression model from sklearn.linear_model was fitted to the training data.
Model Evaluation: The model's performance was assessed using key metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), and the R 2score.
Visualization and Interpretation: A plot was created to visualize the relationship between the features and the target variable. The coefficients of the model were interpreted to understand the influence of each feature on the final prediction
Results and Key Findings
Model Performance:
Mean Absolute Error (MAE): 1381158.895411791
Mean Squared Error (MSE):  3280176595474.013
R² Score: 0.3510473817558726
