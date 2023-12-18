# BackTrader-Moving-Average-

This Python script utilizes the Backtrader framework to implement a buy-only trading strategy based on the Exponential Moving Average (EMA). The financial data is sourced from the Alpha Vantage API.

### Features:

### AlphaVantageData Class:

Custom data feed class designed to integrate Alpha Vantage time series data into Backtrader.

### BuyOnlyExponentialMovingAverageStrategy Class:

Backtrader strategy class implementing a simple buy-only algorithm based on the Exponential Moving Average.

Buys assets when the closing price is above the Exponential Moving Average with a specified period.

### run_backtest Function:

Downloads historical financial data for a specified symbol (e.g., "XAUUSD" for Gold) from Alpha Vantage.

Initializes Backtrader with the custom data feed and the buy-only EMA strategy.

Sets initial capital, commission, and runs the backtest.

Prints starting and ending portfolio values, along with the return percentage.

Visualizes the results using Backtrader's plotting functionality.

### Dependencies:


Backtrader

Pandas

Alpha Vantage Python API

### How to Run:

Execute the script, and Backtrader will simulate the buy-only EMA strategy on the provided financial data. The results, including portfolio values and return percentages, will be displayed in the console. Additionally, a plot of the trading performance will be generated for visual analysis.

Feel free to customize the script or integrate additional features based on your trading preferences or requirements.
