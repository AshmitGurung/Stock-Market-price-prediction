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


# Modules Overview

## 1. data_preprocessing.py

Handles:

-Loading stock data using yfinance.<br>
-Scaling and splitting data for training and testing.

## 2. plotting.py

Provides:

Functions to plot stock prices and moving averages.<br>
Functions to visualize the difference between actual and predicted prices.

## 3. model_prediction.py

Includes:

Functions to load and use the LSTM model for predictions.<br>
Error calculation and scaling back predictions to original price range.

## 4. model_training.py

Handles:

Data preparation for model training.<br>
Training and saving the LSTM model.

## 5. main_app.py

Integrates all modules into a cohesive Streamlit application.<br>
Manages user input, calls necessary functions from other modules, and displays results.


# Future Improvements
-Additional Model Types: Implement and compare different model architectures (e.g., GRU, Transformer).<br>
-Real-Time Predictions: Integrate real-time stock data for up-to-date predictions.<br>
-Model Hyperparameter Tuning: Add functionality to tune hyperparameters through the UI.<br>
-Enhanced Visualization: Improve the visual appeal and interactivity of plots.








