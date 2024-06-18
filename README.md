# MonteCarloSimulation

This project aims to perform portfolio risk management using various methods, including historical VaR, parametric VaR, and Monte Carlo simulations. It calculates the Value at Risk (VaR) and Conditional Value at Risk (CVaR) for a given portfolio of stocks.

## Features

- Fetch historical stock data using Yahoo Finance API
- Calculate historical, parametric, and Monte Carlo VaR and CVaR
- Simulate portfolio performance using Monte Carlo methods
- Visualize the simulation results with matplotlib

## Project Overview
1. Fetch Stock Data
- The script fetches historical data for a given list of stock tickers using the Yahoo Finance API. It calculates the percentage returns, mean returns, and covariance matrix of the stocks.

3. Portfolio Performance
- It calculates the expected returns and standard deviation of the portfolio based on the asset weights, mean returns, and covariance matrix.

4. Value at Risk (VaR) and Conditional Value at Risk (CVaR)
- The script calculates VaR and CVaR using three different methods:
    - Historical VaR and CVaR: Based on historical data
    - Parametric VaR and CVaR: Assuming normal and t-distributions
    - Monte Carlo VaR and CVaR: Using Monte Carlo simulations
4. Monte Carlo Simulation
- It performs a Monte Carlo simulation to estimate the future value of the portfolio over a specified timeframe, plotting the results for visualization.

5. Interpretation of Results
- The script prints and interprets the VaR and CVaR results in layman's terms, helping users understand the potential risk of their portfolio.
