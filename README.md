# Time Series Analysis for Advertising and Currency Data

![Time Series Analysis](time_series_image.jpg)

## Overview

This project delves into the fascinating world of time series analysis, focusing on real-world data pertaining to ads watched per hour and in-game currency spend per day. The project aims to gain insights into the underlying patterns and trends in these time series data, with the ultimate goal of making predictions and understanding the factors that influence these two variables.

### Forecast Quality Metrics

Before diving into the analysis, it's crucial to establish how we measure the quality of our predictions. We'll explore commonly used metrics to assess the accuracy of our forecasts. The project follows a structured methodology of "Move, Smoothe, Evaluate."

### Moving Average

We begin our analysis with a simple hypothesis: "tomorrow will be the same as today." We'll explore the moving average as a baseline for time series prediction. This entails predicting the future value of a variable based on the average of its previous 'k' values.

### Smoothing for Trend Detection

One essential application of moving average is smoothing the original time series to identify trends. This project utilizes Pandas' rolling window function to compute rolling mean trends with different window sizes (4, 12, and 24 hours). Smoothing the data helps reveal underlying patterns and trends in the time series.

### Anomaly Detection

The project also delves into anomaly detection using the moving average approach. We explore how well this simple method can identify anomalies within our data. Additionally, we discuss the limitations of this approach, especially when dealing with seasonality and complex patterns.

### Exponential Smoothing

Exponential smoothing is introduced as a modification to moving average, where weights are assigned to recent observations. This method is used to improve the accuracy of forecasts.

### Time Series Cross-Validation

We explore the importance of time series cross-validation to assess the performance of our models, considering the temporal nature of the data.

### Econometric Approach

The project touches upon stationarity, the process of transforming non-stationary data into a stationary format. This lays the foundation for building SARIMA (Seasonal AutoRegressive Integrated Moving Average) models to capture seasonality and trends effectively.

### ARIMA-Family Models

A brief crash course on ARIMA (AutoRegressive Integrated Moving Average) models and their components is provided. This includes feature extraction, lags of time series, regularization, feature selection, and boosting.

### Looking Beyond: XGBoost

We explore the application of XGBoost, a powerful gradient boosting algorithm, to improve time series forecasting.

## Repository Contents

- Jupyter Notebook (`TimeSeries_Jahnu.ipynb`): Contains the Python code and analysis for time series modeling, visualization, and predictions.
- Dataset (`ads.csv,currancy.csv`): The raw dataset used for this project, encompassing advertising data and currency exchange rates.
- Images: A folder containing images used in the project for data visualization.

## Installation and Requirements

To run the Jupyter Notebook and explore the project, you need the following libraries and tools installed:

- Python (3.x recommended)
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Statsmodels
- Scikit-learn
- XGBoost (if exploring advanced modeling)

## Usage

1. Clone this repository to your local machine.
2. Open the Jupyter Notebook `TimeSeries_Jahnu.ipynb` to explore the project.
3. Execute the code cells to perform data analysis, visualization, and modeling.

Feel free to modify and experiment with the code to enhance your understanding of time series analysis.

## Acknowledgments

This project was created as a learning exercise in time series analysis. Special thanks to the open-source data science community for providing valuable resources and documentation.

## Author

[Jahnu Deka]
[jahnujaan21@gmail.com]


