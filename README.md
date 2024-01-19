### Monthly-Champagne-Sales-forecast-project
Perrin Freres Monthly Champagne Sales Forecast Project

This repository contains a predictive and classifying project for forecasting monthly champagne sales for Perrin Freres, a French champagne house. The dataset used in this project is the "Perrin Freres Monthly Champagne Sales" dataset from Kaggle.

Dataset Description:
The dataset consists of 144 monthly champagne sales records from January 2011 to December 2016, with each record containing variables such as sales, promotional expenditure, price, and quantity discount.

Project Goals:
1. Preprocess the data to handle missing values, outliers, and feature engineering.
2. Split the data into training and testing sets.
3. Train and evaluate multiple time-series models (AR, ARIMA) for monthly champagne sales forecasting.
4. Deploy the selected algorithm in a production environment for real-time sales forecasting.

Project Structure:
The project is organized into the following directories and files:

- perrin_freres_monthly_champagne_sales_forecast/ (root directory)
  - data/ (contains the original dataset)
    - perrinfreresmonthlychampagnesales.csv (original dataset)
    - data_preprocessing.py (preprocessing the data - data wrangling)
    - train_test_split.py (splitting the data into training and testing sets)
    - model_training.py (training and evaluating machine learning algorithms)
