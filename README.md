# Time-Series-Analysis-Yahoo-stock-price

Here is a sample README for this time series analysis project:

# Time Series Analysis of Yahoo Stock Prices

This project performs time series analysis on Yahoo stock price data to identify trends, seasonality, and other patterns.

## Data

The dataset contains daily open, close, high, low, volume, and adjusted close prices for Yahoo stock from November 23, 2015 to November 20, 2020. The data is stored in `yahoo_stock.csv`.

## Analysis

The analysis includes:

- Loading and inspecting the Yahoo stock price data
- Plotting the high and low prices over time
- Plotting the open and close prices over time to visualize overall trends
- Performing additive and multiplicative decomposition on the open, close, high and low prices to extract trend, seasonal, and residual components
- Visualizing the decomposition plots to understand patterns in the data

## Key Findings

- Gradual increase in stock price from 2016-2018
- Two sharp declines in price during 2019 and 2020
- Rise in stock price in second half of 2020
- Seasonal patterns exist in the data
- Periods of high volatility visible in residuals during rapid changes

## Requirements

The analysis requires the following Python packages:

- pandas 
- numpy
- matplotlib
- statsmodels

The code is implemented in a Jupyter notebook - `yahoo_stock_analysis.ipynb`.

## Usage

To use this analysis, simply clone the repository and run the Jupyter notebook. The notebook walks through the step-by-step process for loading, visualizing, and decomposing the Yahoo stock price time series.

## Contributing

Contributions to expand or improve the analysis are welcome! Please open an issue or submit a pull request.
