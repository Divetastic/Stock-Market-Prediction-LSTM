# Stock Market Prediction with LSTM

This project is a deep learning-based model that predicts Google's stock prices using a stacked Long Short-Term Memory (LSTM) neural network. The model was built with Python and TensorFlow, and trained on historical stock data from Yahoo Finance.

## Overview

- *Model Type*: Stacked LSTM with 4 layers
- *Libraries Used*: TensorFlow, Keras, yfinance, NumPy, Matplotlib
- *Target Stock*: Google (GOOG)
- *Performance Metric*: RMSE ≈ 0.001

## How It Works

1. *Data Collection*: Downloaded Google stock data using yfinance.
2. *Preprocessing*: Applied Min-Max scaling (0 to 1) to normalize data.
3. *Model Architecture*:
   - 4 LSTM layers with 50, 60, 80, and 120 neurons
   - Final Dense layer for price output
4. *Training & Prediction*: Trained on normalized data, then inverse-scaled predictions back to real prices.
5. *Evaluation*: RMSE of ~0.001 and strong visual match to actual data.

## Sample Output
![Predictions_vs_actual](https://github.com/user-attachments/assets/52c5d557-a060-4666-97bb-4fcd089e1cc9)
