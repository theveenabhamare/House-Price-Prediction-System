# House Price Prediction System

# Project Overview

This project builds a machine learning model to predict house prices based on various property features such as area, number of bedrooms, bathrooms, and other housing attributes.

The project demonstrates the complete machine learning workflow including data preprocessing, exploratory data analysis, model training, and prediction.

This project is developed as part of the 

## Objectives

* Analyze housing dataset
* Identify key factors affecting house prices
* Train a machine learning model for price prediction
* Evaluate model performance
* Deploy a simple prediction interface

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Streamlit (optional dashboard)

# Project Files

# house_price_prediction.ipynb

Main notebook containing:

* Data loading
* Data cleaning
* Exploratory Data Analysis (EDA)
* Feature selection
* Model training
* Model evaluation

# house_data.csv

Dataset containing house features and price values.

# model.pkl

Saved machine learning model used for prediction.

# app.py

Streamlit web app for predicting house prices.


# Machine Learning Model

The project uses **Linear Regression** to predict house prices.

Model training steps:

1. Data preprocessing
2. Feature selection
3. Train-test split
4. Model training
5. Performance evaluation

# Key Insights

* House area has strong correlation with price.
* Number of bedrooms and bathrooms significantly affects price.
* Larger houses tend to have higher market value.
* Machine learning can help estimate property prices accurately.

# How to Run the Project

Install required libraries:

pip install pandas numpy matplotlib seaborn scikit-learn streamlit

Run notebook:

jupyter notebook house_price_prediction.ipynb

Run prediction app:

streamlit run app.py
