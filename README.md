# Portfolio Backtesting Engine

Quantitative backtesting engine for a personal five-stock portfolio
(NVDA, amzn, AVGO, XOM, pg) Benchmarking against the s&p 500.

Using a Python backtesting engine to calculate the Sharpe ratio, alpha, and beta of a portfolio for measuring performance on an adjusted basis for risk, and run a 10,000-trial Monte Carlo simulation to estimate future outcomes, with results used to fund a real investment of $1,050.

## Functionality
- historical performance backtest of portfolio using custom position weighting
- calculates Sharpe ratio, alpha, beta, max drawdown, VaR
- performs 10,000 trial Monte Carlo simulations to estimate future performance
- uses SPY as comparison index for performance
- automatically creates report for investing in this allocation that includes letter grade

## Main findings
Backtest of this allocation returned +210% over Aug 2023 – Aug 2026 compared to +85% by the S&P 500 over the same timeframe, with Sharpe ratio = 1.45. Based on these results, I have invested real money ($1,050) in this exact allocation, which I will be tracking going forward.

## Tools used
Python, pandas, NumPy, yfinance, matplotlib, seaborn, statsmodels

## Author
[Eshaan Mohammed]
