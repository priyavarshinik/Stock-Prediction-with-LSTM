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

1. The sequence of data points in a time series is crucial. Shuffling or randomizing the data can destroy the temporal structure, leading to misleading results. Time series data often exhibits autocorrelation, where past values influence future values.
2. A time series is stationary if its statistical properties (mean, variance, autocorrelation, etc.) are constant over time.
