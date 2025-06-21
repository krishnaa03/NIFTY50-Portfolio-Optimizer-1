# NIFTY50 Portfolio Optimizer

A comprehensive portfolio optimization and analysis tool for NIFTY50 stocks, built in Python.
This project fetches historical stock data, analyzes correlations, and uses Monte Carlo simulation to find the optimal risk-return portfolio allocation.

## Features

- Fetches historical price data for any selection of NIFTY50 stocks using Yahoo Finance.
- Calculates daily returns, correlations, and visualizes price trends.
- Runs a Monte Carlo simulation to generate thousands of portfolio combinations.
- Identifies the optimal portfolio based on the highest Sharpe Ratio.
- Analyzes risk with Value at Risk (VaR) and Conditional VaR (CVaR).
- Visualizes results with clear, publication-quality plots.

## How to Use

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/nifty50-portfolio-optimizer.git
    cd nifty50-portfolio-optimizer
    ```

2.  **Install dependencies:**
    ```sh
    pip install -r requirements.txt
    ```

3.  **Run the notebook:**
    ```sh
    jupyter notebook Optimizer.ipynb
    ```
    or open in JupyterLab/VS Code.

4.  **Follow the notebook instructions to select stocks, set your investment amount and risk-free rate, and analyze your optimal portfolio!**

## Disclaimer

**This project is for educational and demonstrational purposes only and should not be considered financial advice.** The stock market is volatile, and all investment decisions should be made with the guidance of a qualified financial professional. Past performance is not indicative of future results.

## Requirements

- Python 3.8+
- yfinance
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

(Install with `pip install -r requirements.txt`)


## Project Structure
nifty50-portfolio-optimizer/
├── Optimizer.ipynb
├── requirements.txt
└── README.md
