# Monte Carlo Portfolio Risk Simulator

## Overview

This project uses Monte Carlo simulation to estimate the one-year risk profile of an investment in the SPDR S&P 500 ETF (SPY).

Historical market data is used to estimate return and volatility parameters, which are then used to generate thousands of possible future portfolio outcomes. The project implements both a basic Monte Carlo model and a Geometric Brownian Motion (GBM) model based on the Samuelson-Merton framework.

## Features

* Historical SPY data retrieval using yfinance
* Daily return and volatility estimation
* Monte Carlo simulation of future portfolio values
* Geometric Brownian Motion (GBM) simulation
* Probability of loss estimation
* 95% Value at Risk (VaR)
* 95% Expected Shortfall (ES)
* Probability of losing more than 20%
* Distribution and path visualisations

## Methodology

1. Download five years of historical SPY price data.
2. Calculate daily returns.
3. Estimate historical mean return and volatility.
4. Generate 10,000 simulated one-year portfolio paths.
5. Calculate portfolio risk metrics.
6. Compare a standard Monte Carlo approach with a GBM-based model.

## Technologies Used

* Python
* NumPy
* Matplotlib
* yfinance
* Jupyter Notebook

## Key Concepts

* Monte Carlo Methods
* Stochastic Processes
* Geometric Brownian Motion
* Samuelson-Merton Model
* Value at Risk (VaR)
* Expected Shortfall (ES)
* Portfolio Risk Management
