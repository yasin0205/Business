
# Airline Ticket Price Prediction

This project aims to predict airline ticket prices using multiple machine learning algorithms. The primary focus is on building a robust pipeline involving data preprocessing, feature engineering, model training, evaluation, and optimization.

## Project Overview

The dataset consists of airline ticket information, including features like airline, source, destination, departure time, arrival time, total stops, and price. The goal is to predict ticket prices based on these features using machine learning.

## Features

- **Data Preprocessing**:
  - Handled missing values and date-time inconsistencies.
  - Converted categorical features to numerical using one-hot and label encoding.
  - Addressed outliers using median-based replacement.

- **Feature Engineering**:
  - Extracted meaningful features from existing data (e.g., journey day, month, duration hours).
  - Selected significant features using information gain.

- **Algorithms Used**:
  - Logistic Regression
  - Naive Bayes
  - Random Forest
  - Decision Tree
  - K-Nearest Neighbors

- **Model Evaluation**:
  - Used metrics such as R², MAE, MSE, and RMSE to compare model performance.
  - Hyperparameter tuning using `RandomizedSearchCV` improved Random Forest performance.

## Results

**Random Forest**:
- R² Score: 0.83
- MAE: 1122.85
- RMSE: 1837.56

Comparative evaluation showed Random Forest as the best-performing model after hyperparameter tuning.

