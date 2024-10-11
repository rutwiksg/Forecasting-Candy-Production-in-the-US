# Forecasting-Candy-Production-in-the-US
The project aims to forecast monthly candy production in the US using various time-series forecasting models to identify the most accurate method.

Data Overview: The dataset comprises monthly candy production indices from 2012 to 2022. It shows clear seasonal patterns, with peaks in November and December during the holiday season and troughs in July.

Methods: The following time-series forecasting methods were applied:

Naïve Method: Simple and baseline but struggled with seasonality and trends.
Simple Moving Averages: Used smoothing to capture trends, but higher orders reduced accuracy.
Simple Exponential Smoothing: Weighted recent data but showed some bias in residuals.
Holt-Winters Method: Suitable for seasonal data, improved accuracy, but still had residual fluctuations.
ARIMA Model: Selected as the best model for forecasting based on lowest error values and residual analysis.
Results:

The ARIMA model (ARIMA(0,0,0)(0,1,0)[12] with drift) was the most accurate, outperforming the other models.
Forecast accuracy was measured through ME, RMSE, MAE, and residual patterns, where ARIMA had the best fit.
Conclusion: ARIMA is the best model for forecasting candy production, predicting an increasing trend in the next one to two years, with seasonal peaks during the holiday months.
