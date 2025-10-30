# Trading application

This project is a mini trading application in Python that simulates simple cryptocurrency trading strategies for Bitcoin (BTC) and Ethereum (ETH). The focus is on strategy logic, trade logging, and performance reporting rather than live trading. All code is contained in the file trading_application.ipynb. For further elaboration and documentation, see [Notion](https://www.notion.so/Trading-application-documentation-299f65869f078002854cf3458a37b190?source=copy_link).

## Functions
- Collect historical BTC and ETH price data from Yahoo Finance
- Compute performance metrics 
- Generate plots of prices overlayed with trades, equity and drawdown
- Implement momentum with correlation filter strategy
- Execute trades with entry/exit logging and compute equity and returns

## Outputs 
- Show each trade with asset name, entry/exit time, side, price and size
- Key performance metrics such as Sharpe ratio, Sortino ratio, maximum drawdown, win rate, total PnL
- Plots of BTC and ETH prices with trade (buy/sell) markers
- Plots of equity and drawdown over time 

## Dependencies
The required Python packages are the following:
- pandas
- numpy
- yfinance
- matplotlib
- datetime



