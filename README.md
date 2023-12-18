# BackTrader-Moving-Average-

 This Python script uses the Backtrader library to implement a trading strategy based on the Exponential Moving Average (EMA). The financial data is obtained from Alpha Vantage API.

Key Components:

AlphaVantageData Class:
Custom data feed class for integrating Alpha Vantage time series data into Backtrader.
BuyOnlyExponentialMovingAverageStrategy Class:
Backtrader strategy class that generates buy orders when the closing price is above the Exponential Moving Average (EMA) with a specified period (e.g., 50).
run_backtest Function:
Downloads historical financial data for a specified symbol (e.g., "XAUUSD" for Gold) from Alpha Vantage.
Initializes Backtrader with the custom data feed and the EMA strategy.
Sets initial capital, commission, and runs the backtest.
Prints starting and ending portfolio values, along with the return percentage.
Visualizes the results using Backtrader's plotting functionality.
Usage:


Backtrader
Pandas
Alpha Vantage Python API
