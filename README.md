# Stock-Prediction-with-LSTM
Predicting stock market price with LSTM and exploring a few other regression models.

Stock market prices change every day, and predicting the prices is extremely difficult. This project will give a tour, starting with the stock market, a description of stock data, and how to forecast it. 

*Topics:*

1. Stock Market
2. Loading data
3. Visualising the data
4. Preparing the data
5. Selecting and training the model
6. Evaluating and Fine-tuning the model

# Stock Market:


# Conditions for Time series data: 

The stock market is a time series data, so there are several important considerations to ensure that your analysis, modelling, and predictions are valid and meaningful. 

1. The sequence of data points in a time series is crucial. Shuffling or randomising the data can destroy the temporal structure, leading to misleading results. Time series data often exhibits autocorrelation, where past values influence future values.
2. A time series is stationary if its statistical properties (mean, variance, autocorrelation, etc.) are constant over time. If your data is not stationary, you might need to apply transformations (like differencing, detrending, or log transformations) to make it stationary. You can use tests like the Augmented Dickey-Fuller (ADF) or the KPSS test to check for stationarity.
3. If not accounted for, Long-term upward or downward movements in the data can affect model accuracy. Techniques like differencing can help remove trends.
4. Regular patterns that repeat over fixed periods (e.g., daily, weekly, yearly) need to be identified and modelled separately if they exist. Decomposing the time series into trend, seasonal, and residual components can be helpful.
5. Instead of randomly splitting the data for training and testing, use time series-specific methods like time-based splits (e.g., time series split, walk-forward validation).
6. With complex and high-frequency data like stock prices, machine learning models (e.g., LSTM, Prophet) or deep learning models (e.g., RNN, CNN) might be more appropriate, especially if capturing non-linear patterns.
7. Always evaluate your model on a separate test set representing future periods not seen during training. Use techniques like time series cross-validation to ensure robust evaluation.
8. Common metrics for time series forecasting include Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), Mean Absolute Percentage Error (MAPE), and directional accuracy (critical for stock market predictions).











