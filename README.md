# Monte-Carlo-Risk-Prediction-Tech_Stocks

## Overview

This project utilizes the Monte Carlo Analysis Method to analyze and predict the risk associated with future investments in the stocks of Apple (AAPL), Microsoft (MSFT), Meta (META), and NVIDIA (NVDA). The Monte Carlo Method is a statistical technique that leverages randomness to solve problems that might be deterministic in principle. This method is particularly useful in financial modeling to predict the behavior of asset prices and assess the risk involved.

## Project Structure

The project is divided into the following steps:

### Step 1: Data Preparation
1.1 **Data Collection:** Gather historical stock price data for AAPL, MSFT, META, and NVDA.
1.2 **Data Processing:** Clean and preprocess the data to ensure it's ready for analysis.

### Step 2: Visualizations
2.1 **Plotting Simulated Price Paths:** Generate and visualize simulated price paths using the Geometric Brownian Motion (GBM) model.
2.2 **Percentile Bands and Mean Path:** Highlight key percentiles (e.g., 5th, 50th, 95th) and overlay the mean path to illustrate the range of possible future prices.

### Step 3: Error Metrics
3.1 **Evaluating and Simulating Accuracy:** Calculate error metrics such as Mean Absolute Error (MAE) and Root Mean Square Error (RMSE) to assess the accuracy of the simulations.

### Step 4: Portfolio Context
4.1 **Simulating Portfolio Returns:** Simulate portfolio returns based on the weighted combination of the selected stocks.
4.2 **Stress Testing and Visualizations:** Conduct stress testing to understand the behavior of the portfolio under different market conditions and visualize the results.

## Monte Carlo Analysis Method

The Monte Carlo Method involves the use of random sampling and statistical modeling to estimate mathematical functions and mimic the operations of complex systems. In this project, we employ the Geometric Brownian Motion (GBM) model to simulate the future price paths of the selected stocks. The GBM model is widely used in finance for modeling stock prices due to its ability to capture the stochastic nature of financial markets.

### Key Concepts

- **Random Sampling:** Utilizing random variables to produce different possible outcomes in a simulation.
- **Geometric Brownian Motion (GBM):** A continuous-time stochastic process in which the logarithm of the randomly varying quantity follows a Brownian motion with drift.
- **Error Metrics:** Metrics such as MAE and RMSE are used to evaluate the accuracy of the simulated paths by comparing them with actual historical data.

## How to Use

1. **Clone the Repository:** 
   ```bash
   git clone "https://github.com/JALAJ-PATEL/Monte-Carlo-Risk-Prediction-Tech_Stocks.git"


