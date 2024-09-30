# AirPassenger-Sarimax-and-Arima
# ARIMA and SARIMA Forecasting: Airline Passenger Dataset
- This project involves time series forecasting on the Airline Passenger dataset using ARIMA and SARIMA models. We start by using the auto_arima function from the pmdarima package to determine the optimal model parameters. After performing stationarity tests, autocorrelation, and partial autocorrelation analyses, we build and evaluate ARIMA and SARIMA models to predict the next 10 years of airline passengers. SARIMA provides a more accurate prediction.


- Dataset Overview
- The Airline Passenger dataset contains the monthly number of passengers for an airline over several years. This dataset is commonly used to demonstrate time series analysis and forecasting techniques.

- Columns: Date, #Passengers
- Time Range: 1949 - 1960
- Goal: Predict the number of passengers for the next 10 years.
- Steps to Perform
- Auto ARIMA: Use pmdarima.auto_arima to find the optimal order of the ARIMA model.
- Stationarity Testing: Perform the ADF test (Augmented Dickey-Fuller) to check the stationarity of the time series.
- ACF & PACF: Plot Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF) to understand the data's autocorrelation structure.
- ARIMA Model: Use the identified order from auto_arima and build an ARIMA model to forecast the next 10 years of passengers.
- SARIMA Model: Build a SARIMA model that captures both seasonal and non-seasonal components of the time series, leading to better accuracy.
- Forecast Evaluation: Compare the ARIMA and SARIMA model performance based on predicted values and visualize the forecasts.
