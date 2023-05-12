
# Portfolio Optimization with Riskfolio-Lib

This repository contains code for optimizing investment portfolios using the Riskfolio-Lib library in Python. The code utilizes historical stock price data to estimate expected returns and covariance matrices, and then applies various risk measures and objective functions to find the optimal portfolio allocation.

## Introduction

The portfolio optimization code in this repository uses the Riskfolio-Lib library, which provides a set of tools for risk analysis and portfolio optimization. The code demonstrates how to estimate expected returns and covariance matrices from historical data, and how to apply different risk measures and objective functions to find optimal portfolio allocations.

## Installation

To run the code in this repository, you need to have Python 3.x and the following libraries installed:

- yfinance
- pandas
- requests
- matplotlib
- seaborn
- riskfolio-lib

You can install these dependencies using pip:

```bash
pip install yfinance pandas requests matplotlib seaborn riskfolio-lib
```

## Usage

To use the portfolio optimization code, follow these steps:

1. Modify the `stocks` and `asset` lists in the code to include the stock tickers you want to analyze.
2. Set the desired start and end dates for the historical data.
3. Run the code and observe the optimized portfolio allocations for different risk measures and objective functions.

## Examples

The code includes examples of optimizing portfolios using different risk measures and objective functions. These examples demonstrate how to apply the Mean Absolute Deviation (MAD), Expected Shortfall (ES), Conditional Value at Risk (CVaR), Conditional Drawdown at Risk (CDaR), Expected Downside Risk (EDaR), and Mean-Variance (MV) risk measures with the MinRisk and Sharpe ratio objective functions.

## Contributing

Contributions to this repository are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.




