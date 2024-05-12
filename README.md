# Sales Forecasting Analysis

## Introduction

This project aims to forecast sales for the next two years based on historical sales data using time series analysis techniques. The dataset contains information about sales transactions, including order dates, sales amounts, and other relevant attributes.

## Data Cleaning and Manipulation

The dataset was cleaned and manipulated to ensure data integrity and consistency. Steps included renaming columns, handling missing values and duplicates, converting date columns to the appropriate format, and resampling the data to aggregate sales on a monthly basis.

## Exploratory Data Analysis (EDA)

EDA was conducted to gain insights into sales trends over time. Key observations include daily, monthly, and yearly sales trends, as well as seasonal decomposition analysis to identify underlying patterns.

## Checking Stationarity

An Augmented Dickey-Fuller (ADF) test was performed to ensure stationarity in the time series data, allowing us to proceed with modeling.

## Feature Engineering

Relevant features such as day, month, and year were extracted from the order date to aid in modeling.

## Model Building

The Seasonal Autoregressive Integrated Moving Average with Exogenous Regressors (SARIMAX) model was utilized for forecasting. The model was trained on historical data and used to predict future sales.

## Model Evaluation

The forecasting model was evaluated using metrics such as Mean Absolute Error (MAE), Mean Absolute Percentage Error (MAPE), and Mean Squared Error (MSE) on the testing dataset.

- MAE: 16459.69
- MAPE: 36.77%
- MSE: 377195390.05

## Results and Conclusion

The forecasting model demonstrated promising results in predicting future sales, providing valuable insights for business planning and strategy.

## Future Work

Potential areas for future work include refining the forecasting model for improved accuracy, incorporating external factors for enhanced forecasting, and continuous monitoring and updating of the model.

## Additional Files

The Jupyter Notebook containing the code for this analysis is available as one of the files in this repository.
