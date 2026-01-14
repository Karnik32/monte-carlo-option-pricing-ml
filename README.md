# monte-carlo-option-pricing-ml
This project uses Monte Carlo simulation to generate accurate European call option prices and trains a neural network surrogate model to provide fast approximations. ML predictions are validated against Monte Carlo results to ensure reliability within the trained input range.

# Monte Carlo + Machine Learning Option Pricing

This project explores how Monte Carlo simulation and machine learning can be used
together for option pricing.

Monte Carlo simulation is used to generate accurate prices for a European call
option. A neural network is then trained on this simulated data to act as a fast
approximation model. The ML output is compared with the Monte Carlo result to
check accuracy.

The goal of this project is to understand the trade-off between accuracy and
speed when using simulation-based models and machine learning in quantitative
finance.

## How it works
- Simulates option prices using Monte Carlo methods
- Trains a neural network on the simulated data
- Uses the trained model to predict prices for new inputs
- Validates ML predictions against Monte Carlo results
