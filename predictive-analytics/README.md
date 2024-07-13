# House Price Prediction Project using Predictive Analytics

## Overview
This project focuses on predicting house prices using advanced data science techniques and various machine learning models.

## Key Highlights

- **Data Preprocessing**: Handled missing values, normalized data, and removed outliers to ensure data quality.
- **Exploratory Data Analysis (EDA)**: Performed EDA to understand the data distribution, relationships, and feature importance.
- **Feature Engineering**: Created new features and transformed existing ones to enhance model performance.
- **Modeling**: Implemented and compared multiple regression models including Gradient Boosting Regressor, RidgeCV, Kernel Ridge, LassoCV, and ElasticNetCV.
- **Model Validation**: Evaluated models using R-squared, RMSE, and Mean Absolute Error to identify the best performing model.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scipy
- Scikit-learn

## Data Preprocessing Steps

- **Handling Missing Values**: Used methods like filling with 'None', median, mode, and zeros based on the feature context.
- **Normalization**: Applied log transformation to normalize skewed features.
- **Outlier Removal**: Identified and removed outliers to improve model accuracy.

## Exploratory Data Analysis

- **Scatter Plots**: Visualized relationships between features and the target variable (SalePrice).
- **Pair Plots**: Explored interactions between multiple features.
- **Distribution Plots**: Examined the distribution of the target variable and applied log transformation for normalization.
- **Heatmap**: Visualized correlations between numeric features to identify important predictors.

## Feature Engineering

- **Skewness Correction**: Applied log transformation to highly skewed numeric features.
- **Categorical Encoding**: Converted categorical features to binary using pandas get_dummies.

## Modeling and Evaluation

- **Cross-Validation**: Used K-Fold cross-validation to ensure robust model performance.
- **Model Comparison**: Compared performance of various models using cross-validation scores.
- **Best Model**: Identified LassoCV as the best model based on minimum cross-validation error and highest R-squared.

## Model Performance

- **R-Squared**: Measures how close the data are to the fitted regression line. Best possible score is 1.0.
- **RMSE (Root Mean Squared Error)**: Measures the error between predicted and actual values.
- **Mean Absolute Error**: Measures the average magnitude of errors in predictions.

## Best Model

The best model identified is the LassoCV Regression, which achieved the highest R-squared and the lowest RMSE and Mean Absolute Error among all models tested.

## Future Work

- **Hyperparameter Tuning**: Further tune hyperparameters to improve model performance.
- **Pipeline and GridSearchCV**: Enhance models by adding pipeline and grid search for better parameter optimization.

This project demonstrates my ability to preprocess data, perform exploratory analysis, engineer features, build and validate multiple machine learning models, and identify the best performing model for predicting house prices.

