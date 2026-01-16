# Stock-Price-Prediction-ML- (using Linear Regression)


##  Project Description
The art of forecasting stock prices has been a difficult task for many researchers and analysts. This project implements a Linear Regression model to provide supportive information, such as the future direction of the stock market, to help traders, investors, and analysts make informed decisions. Because successful investment depends on knowing the future situation of the market, this model offers a clear trend-based forecast.



##  How the Model Works
Linear Regression is a fundamental machine learning algorithm used to find the linear relationship between a dependent variable (Stock Price) and an independent variable (Time).

1. **Trend Identification:** The model analyzes historical data from 2024 to 2026 to find the "line of best fit."
2. **Mathematical Foundation:** It uses the equation $y = mx + c$ to represent the market trend.
3. **Forecasting:** By extending the linear trend into the future, the model helps investors understand the long-term direction of the stock.

##  Features
* **Real-Time Data:** Uses the `yfinance` library for up-to-date market statistics.
* **Predictive Analysis:** Includes a future price predictor for upcoming market days.
* **Visualization:** Clear graphical representation of actual prices vs. the calculated trendline.

##  How to Run
1. Open the `.ipynb` file in **Google Colab**.
2. Update the `ticker` variable to your desired stock (e.g., 'AAPL', 'MSFT').
3. Run all cells to generate the trend analysis and future forecast.
