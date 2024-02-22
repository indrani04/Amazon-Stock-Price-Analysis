# Project Title: Time Series Analysis of Amazon Stock Prices
# Abstract:
This project delves into the analysis and prediction of historical stock price data of Amazon, a prominent global technology and e-commerce corporation. By analyzing monthly closing prices from 2007 to 2021 and validating the model on data from 2022, the research aims to uncover underlying trends and patterns, offering valuable insights for investors and analysts.

# Introduction:
The analysis focuses on understanding and predicting trends in financial markets using historical stock price data sourced from Yahoo Finance. Monthly closing prices of Amazon stock from 2007 to 2021 are utilized for training, with data from 2022 used for validation.

# Analysis:
The time series plot reveals an increasing trend, possibly quadratic or exponential in nature, with notable spikes indicating external events.
Auto-Correlation Function (ACF) analysis suggests a trend with no yearly seasonality but significant cyclic behavior.
Regression analysis confirms the exponential nature of the trend, with a recommended log transformation followed by linear regression. The best regression model includes lag terms to improve prediction accuracy.
# Forecasts:
Double Exponential Smoothing (Holt's Method) is applied to capture the linear trend in the data, yielding accurate forecasts for immediate time indices.
ARIMA models are explored, but due to the variability in the series, ARIMA forecasts tend to overestimate the data.
Bootstrap techniques are employed to generate 1000 samples and integrate residual errors into forecasts, yielding predictions aligned with the dataset pattern.
# Conclusion:
The analysis showcases various models for predicting Amazon stock prices, with double exponential smoothing emerging as the most suitable for capturing trends in the provided dataset. While exponential models excel in short-term forecasting, regression or ARIMA models may offer better predictive capabilities over extended periods.

# Future Work:
Future research could explore incorporating external factors such as economic indicators and market trends to enhance the accuracy and robustness of stock price forecasts.

# References:
[1] “Amazon.com, Inc. (AMZN) Stock Price, News, Quote & History - Yahoo Finance.” Accessed: Dec. 07, 2023. [Online]. Available: https://finance.yahoo.com/quote/AMZN/![image](https://github.com/indrani04/Amazon-Stock-Price-Analysis/assets/58809526/ecde09f4-9ab8-4e19-802e-5974b318a1c9)

