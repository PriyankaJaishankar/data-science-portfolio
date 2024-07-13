# Production Quality Analysis

## Overview
This project focuses on analyzing the quality of production using a generated dataset. The aim is to identify key factors influencing product quality and propose strategies for improvement based on statistical analysis.

## Key Highlights

- **Data Generation**: Created a synthetic dataset simulating production data including production times, temperature, humidity, and quality scores.
- **Data Cleaning**: Handled missing values, duplicates, and standardized column names.
- **Exploratory Data Analysis (EDA)**: Performed EDA to understand the data distribution, relationships, and feature importance.
- **Statistical Analysis**: Conducted ANOVA and t-tests to determine the influence of various factors on quality scores.
- **Strategy Proposal**: Proposed strategies for improving product quality based on the analysis.

## Technologies Used

- Python
- Pandas
- NumPy
- Scipy
- Statsmodels
- Matplotlib
- Seaborn

## Data Generation

Generated a dataset with the following features:
- **Production_Date**: Date of production.
- **Product_ID**: Unique identifier for each product.
- **Production_Time**: Time taken for production (in minutes).
- **Temperature**: Temperature during production (in Celsius).
- **Humidity**: Humidity level during production (in percentage).
- **Quality_Score**: Quality score of the product (0 to 100).

## Data Preprocessing Steps

1. **Handle Missing Values**: Filled missing values with the mean of respective columns.
2. **Handle Duplicates**: Removed duplicate records.
3. **Convert Date Column**: Converted the production date column to datetime format.
4. **Standardize Column Names**: Standardized column names to lowercase.

## Exploratory Data Analysis

- **Histograms**: Visualized the distribution of numeric columns.
- **Pairplot**: Visualized relationships between features.
- **Correlation Analysis**: Computed and visualized the correlation matrix to identify key predictors.
- **Quality Score Distribution**: Analyzed the distribution of the quality score.

## Statistical Analysis

- **Descriptive Statistics**: Provided summary statistics of the dataset.
- **ANOVA**: Conducted ANOVA to determine the influence of temperature, humidity, and production time on quality score.
- **T-tests**: Performed t-tests to analyze the impact of each factor on quality scores.

## Analysis Results

- **ANOVA Results**: Identified significant factors influencing quality score.
- **T-test Results**: Highlighted the impact of temperature, humidity, and production time on quality score.

## Proposed Strategies for Improving Product Quality

Based on the statistical analysis, the following strategies are proposed:

1. **Optimize Temperature**: Adjust temperature settings as it significantly influences product quality.
2. **Optimize Humidity**: Adjust humidity levels as it significantly influences product quality.
3. **Optimize Production Time**: Modify production time as it significantly influences product quality.

## Conclusion

This project demonstrates the process of generating, cleaning, and analyzing production data to identify factors influencing product quality and propose actionable strategies for improvement.

## Future Work

- **Data Collection**: Collect real production data for more accurate analysis.
- **Advanced Modeling**: Use advanced machine learning models to predict quality scores.
- **Hyperparameter Tuning**: Further tune statistical models to enhance analysis accuracy.

