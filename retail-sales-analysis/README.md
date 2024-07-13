# Online Sales Analysis and Prediction

## Overview
This project focuses on analyzing and predicting online sales using machine learning techniques. The dataset used contains information about sales transactions including quantities sold, unit prices, dates, and countries. The goal is to gain insights into sales patterns, identify influential factors, and build predictive models to forecast sales accurately.

## Key Highlights

- **Data Loading**: The dataset (`online_sales.csv`) is loaded and initial exploratory analysis is performed.
- **Data Cleaning**: Handling missing values, duplicates, converting data types, and standardizing column names.
- **Exploratory Data Analysis (EDA)**: Visualizing data distributions, exploring trends over time, analyzing correlations between variables, and identifying key relationships.
- **Feature Engineering**: Creating additional features such as total sales, extracting time-based features (year, month, day, hour), and removing outliers.
- **Statistical Analysis**: Utilizing linear algebra techniques like correlation matrices and principal component analysis (PCA) for dimensionality reduction.
- **Machine Learning Models**: Implementing various regression models including Linear Regression, Ridge Regression, Lasso Regression, and Random Forest Regressor.
- **Model Evaluation**: Assessing model performance using metrics like Mean Squared Error (MSE) and R-squared (R2), and visualizing actual vs. predicted sales.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Workflow

1. **Data Preprocessing**:
   - Load the dataset and perform initial data exploration.
   - Clean the data by handling missing values, duplicates, and converting data types.
   - Engineer new features and standardize column names.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize data distributions using histograms.
   - Analyze trends over time in sales.
   - Explore relationships between variables using pair plots and correlation matrices.

3. **Feature Engineering**:
   - Create additional features such as total sales and extract time-based features.
   - Remove outliers based on sales values and standardize numerical features.

4. **Machine Learning Modeling**:
   - Split data into training and testing sets.
   - Implement various regression models (Linear Regression, Ridge Regression, Lasso Regression, Random Forest Regressor).
   - Evaluate model performance using MSE and R2 scores.

5. **Results and Insights**:
   - Visualize and interpret model predictions.
   - Identify key factors influencing sales.
   - Provide recommendations based on analysis for improving sales strategies.
