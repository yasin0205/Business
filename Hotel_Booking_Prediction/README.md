
# Hotel Booking Cancellation Prediction

This project predicts whether a hotel booking will be canceled based on various features like lead time, booking changes, and customer type. The aim is to assist hotels in reducing booking cancellations and improving revenue management.

## Project Overview

The dataset contains information on hotel bookings, including customer details, booking specifics, and stay information. This project employs machine learning to predict booking cancellation status and provides insights into cancellation trends.

## Features

### Data Preprocessing:
- Replaced missing values and filtered invalid entries (e.g., zero adults, children, and babies simultaneously).
- Encoded categorical variables using mean encoding for better model interpretability.
- Addressed skewness and outliers using log transformations.

### Feature Engineering:
- Conducted correlation analysis to select significant features.
- Applied Lasso regression for feature selection.

### Algorithms Used:
- Logistic Regression
- Naive Bayes
- Random Forest
- Decision Tree
- K-Nearest Neighbors

### Model Evaluation:
- Used metrics such as accuracy, R², MAE, MSE, and RMSE for performance comparison.
- Random Forest with hyperparameter tuning achieved the best results.

## Results

**Random Forest Performance**:
- Accuracy: ~95.46%
- R² Score: 0.87
- MAE: ~0.07
- RMSE: ~0.18

Comparative evaluation showed Random Forest as the best-performing model after hyperparameter tuning.

