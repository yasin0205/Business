
# Stock Price Prediction Using Time Series Data

This project predicts the Volume Weighted Average Price (VWAP) of stocks using time-series data and machine learning techniques. The primary focus is on feature engineering for time-series data and model training using ARIMA.

## Project Overview

The dataset includes stock attributes like Open, High, Low, Close, VWAP, Volume, and Trades. The goal is to predict the VWAP using these features and rolling statistics.

## Features

- **Data Preprocessing**:
  - Managed missing values and set the date as the index for time-series compatibility.
  - Created a clean dataset with essential stock attributes.

- **Feature Engineering**:
  - Generated rolling mean and standard deviation features for attributes like High, Low, Volume, Turnover, and Trades.
  - Ensured lag features were aligned with predictive modeling needs.

- **Algorithms Used**:
  - Auto ARIMA for time-series forecasting with exogenous variables.

- **Model Evaluation**:
  - Used RMSE and MAE to evaluate model accuracy.
  - Forecasted VWAP was plotted against actual values for visualization.

## Results

**ARIMA Model**:
- RMSE: ~187.73
- MAE: ~124.63

The forecast closely follows the actual VWAP trends, as shown in the prediction plots.

