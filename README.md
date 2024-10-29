# Stock-market-price-prediction

This project aims to predict stock prices using historical data and machine learning techniques. The prediction model is built using LSTM neural networks to provide accurate forecasting based on trends.

## Features

- Fetch real-time stock data from Yahoo Finance using `yfinance`.
- Data preprocessing and manipulation with `pandas` and `numpy`.
- Build predictive models using `tensorflow` and `keras`.
- Visualize stock price trends and predictions using `matplotlib`.
- Deploy the prediction model in an interactive web app using `streamlit`.
  

## Usage

# Predicting Stock Prices
1.Launch the Application: Run main_app.py using Streamlit.
2.Enter Stock Symbol: Input the stock symbol (e.g., 'GOOG') in the provided text box.
3.Visualize Stock Data: View historical data and moving averages.
4.Predict Prices: The app will display predicted prices alongside actual prices. Analyze the prediction accuracy using visual plots and error metrics.

# Training a New Model
1.Navigate to the "Train Model" Tab.
2.Enter Stock Symbol and Date Range: Input the stock symbol and select the date range for training data.
3.Train the Model: The app will train a new LSTM model based on the provided data and save it for future predictions.

# Dependencies
-numpy<br>
-pandas<br>
-yfinance<br>
-keras<br>
-tensorflow<br>
-streamlit<br>
-matplotlib<br>
-scikit-learn<br>

For detailed version information, see the requirements.txt file.


#Modules Overview

##1. data_preprocessing.py

Handles:

-Loading stock data using yfinance.<br>
-Scaling and splitting data for training and testing.








