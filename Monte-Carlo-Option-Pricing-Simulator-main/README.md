
# Monte Carlo Option Pricing Simulator

A Python project that estimates the prices of European Call and Put options using Monte Carlo simulation and compares them with the Black-Scholes model.

## About the Project

This project simulates different possible stock price movements to understand how option prices can change over time. It uses Geometric Brownian Motion (GBM) to generate stock price paths and calculates option prices based on the simulation results.

It also shows animated plots to make the results easier to understand.

## Features

- Simulates stock prices using GBM.
- Calculates European Call and Put option prices.
- Compares results with Black-Scholes prices.
- Displays stock price movements and pricing results through plots.
- Includes adjustable pricing parameters.

## Tech Stack

- Python
- NumPy
- Matplotlib
- SciPy

## Project Structure

- `main.py` – Runs the simulation and displays the results.
- `utils.py` – Contains the simulation and pricing functions.
- `requirements.txt` – Lists the required Python packages.
- `README.md` – Project documentation.

## How to Run

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the simulator:

```bash
python main.py
```

## Parameters

You can adjust the strike price, volatility, risk-free rate, and time to maturity to see how they affect option prices.

## What I Learned

- Basics of Monte Carlo simulation.
- Simulating stock price movements using GBM.
- Understanding European options and the Black-Scholes model.
- Comparing simulated prices with theoretical prices.
- Visualizing financial data using Python.




