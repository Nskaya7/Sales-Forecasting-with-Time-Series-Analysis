# Sales-Forecasting-with-Time-Series-Analysis
This project forecasts retail store sales using two classical time series approaches, ARIMA and Facebook Prophet, on the Rossmann Store Sales dataset. The full forecasting workflow is covered, from stationarity testing using the Augmented Dickey-Fuller test and ACF/PACF analysis through to model evaluation and seasonality decomposition.
ARIMA is fitted manually based on the stationarity analysis while Prophet is configured with weekly and yearly seasonality and requires minimal tuning. Both models are evaluated on an 80/20 train-test split using MAE and RMSE. Prophet's component plot breaks down the trend, weekly pattern, and yearly seasonality separately, which gives useful insight beyond raw forecast numbers. For retail sales with strong seasonal patterns, Prophet generalises better out of the box while ARIMA offers more control over the modelling process.


Built with Python, statsmodels, Facebook Prophet, Pandas, NumPy, and Matplotlib.
