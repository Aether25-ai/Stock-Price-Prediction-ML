# Stock-Price-Prediction-ML

## Description
The forecasting of stock prices is a complex challenge for researchers and financial analysts. This project utilizes Machine Learning to provide a supportive system for traders and investors by identifying future market directions. Given the high interest among investors in predicting market situations for successful investment, this model offers a data-driven approach to analysis.

## Model Architecture: LSTM


The model utilizes **Long Short-Term Memory (LSTM)**, a specialized Recurrent Neural Network (RNN) designed for time-series forecasting. Unlike standard neural networks, LSTM has a "memory" cell that allows it to retain information from previous time steps, making it ideal for stock market data where past trends heavily influence future prices.

**How it works:**
1. **Data Ingestion:** Scrapes real-time market data from 2024 to 2026 via Yahoo Finance.
2. **Feature Scaling:** Uses `MinMaxScaler` to normalize data for efficient gradient descent.
3. **Sequential Processing:** The model processes a 30-day sliding window of historical prices to predict the following day's closing price.
4. **Optimization:** Uses the `Adam` optimizer and `Mean Squared Error` loss function to minimize prediction gaps.

## Features
- **Modern Dataset:** Analyzes data specifically from 2024 to 2026.
- **Deep Learning:** Implements a multi-layer LSTM architecture.
- **Supportive Analytics:** Provides visualization of actual vs. predicted trends to assist in decision-making.

## Implementation
1. Open the `.ipynb` file in **Google Colab**.
2. Install dependencies: `!pip install yfinance`.
3. Run the notebook to generate the 2026 forecast plot.
