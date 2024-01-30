## Real Estate Price Prediction

### Overview
This project focuses on predicting the price of real estate in Bangalore using the Bengaluru House Price dataset available on Kaggle (Bengaluru House Price Data). The dataset consists of 13,321 rows and 9 columns.

### Project Highlights
Data Cleaning and Preprocessing: The raw dataset was cleaned and preprocessed to handle missing values, outliers, and other data inconsistencies.

Feature Engineering and Dimensionality Reduction: New features were created to enhance model performance, and dimensionality reduction techniques were applied to streamline the dataset.

Outlier Detection and Removal: Outliers were identified and removed to ensure the model's robustness and accuracy.

Web Application: A web application was developed using Flask, HTML, CSS, and JavaScript to provide an interactive interface for users to predict real estate prices based on input parameters.

### Dataset
The dataset used for this project contains information about various aspects of real estate properties in Bangalore, including location, size, total_sqft, bath, balcony, etc. Each row represents a unique property.

### Web Application
The web application allows users to input details such as area (square feet), number of bedrooms (BHK), number of bathrooms, and location. Upon clicking the "Estimate Price" button, the application predicts the real estate price using the underlying machine learning model.

### Technologies Used
Flask
HTML
CSS
JavaScript
Python
Pandas, NumPy, Scikit-Learn for data processing and modeling

### Model Used 
Linear Regression: Demonstrated strong performance, effectively capturing relationships in the real estate dataset, outperforming Lasso Regression and Decision Tree Regression.
