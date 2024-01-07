# Dynamic-Pricing-Strategy

## Overview
This project explores a dynamic pricing strategy for ride-sharing services by analyzing historical data, calculating demand and supply multipliers, and forecasting ride costs using time series and regression modeling.

## Dependencies
- Pandas
- NumPy
- Plotly
- Matplotlib
- Scikit-learn

## Data
The dataset `dynamic_pricing.csv` includes information such as the number of riders, number of drivers, vehicle type, expected ride duration, and historical cost of rides, enabling the analysis of pricing trends.

## Preprocessing
Data preprocessing involves converting categorical data into numerical, handling missing values, and dealing with outliers. The 'Time Period' column is formatted into datetime, and growth rates are calculated to understand the demand-supply impact on pricing.

## Model Training and Evaluation
An ARIMA model is used to forecast future subscription trends, while a Random Forest regression model predicts dynamic pricing costs based on features like rider count, driver availability, and ride duration. Model performance is evaluated through actual vs. predicted value comparisons.

## Usage
To use this project:
1. Install all dependencies.
2. Run the preprocessing pipeline to prepare the dataset.
3. Fit the ARIMA and Random Forest models on the data.
4. Use the trained models to predict future prices and analyze the effectiveness of the dynamic pricing strategy.

## Results
The analysis results in:
- Scatter and box plots visualizing the relationship between ride duration, cost, and vehicle type.
- A correlation matrix identifying the relationship between different features.
- A calculated dynamic pricing strategy reflecting demand-supply adjustments.
- Predictive analysis showcasing potential future ride costs and the profitability of rides under dynamic pricing versus historical pricing.

The predictive models and their visualizations serve to optimize pricing strategies in real-time, balancing profitability with market conditions.

