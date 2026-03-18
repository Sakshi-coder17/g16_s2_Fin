# Probability_group-16

📉 Market Crash Prediction using Bayesian Generalised Pareto Regression
Overview:
Financial markets don’t collapse gradually—they break at the extremes, and this project focuses on modeling those rare but high-impact crash events using Extreme Value Theory combined with Bayesian Generalised Pareto Regression to better understand and quantify tail risk.

Objective:
The objective of this project is to estimate the probability and severity of extreme market losses by modeling tail distributions, enabling a more realistic assessment of crash risk beyond traditional average-based financial models.

Core Idea:
Instead of chasing noisy day-to-day fluctuations, this approach isolates extreme negative returns, fits a Generalised Pareto Distribution to those tail events, and applies Bayesian reasoning to estimate parameters, capturing uncertainty rather than ignoring it.

Methodology:
The system processes historical financial data to compute returns, identifies threshold exceedances representing extreme losses, models them using a Generalised Pareto Distribution, estimates the parameters via Maximum Likelihood Estimation in a deterministic setup, and extends the framework with Bayesian inference to improve robustness and interpretability.

Progress:
A working modelling pipeline has been developed that successfully identifies extreme events, fits the GPD model, and performs deterministic parameter estimation, with initial simulations producing stable and interpretable crash-risk estimates.

How to Run:
Clone the repository, install the required dependencies, and run the simulation script to generate crash-risk estimates and visualisations using the implemented deterministic pipeline.

Expected Output:
The model produces quantitative estimates of tail risk, including crash probabilities and extreme-loss measures, along with visual insights into the behaviour of rare yet impactful market events.

Key Insight:
The biggest takeaway is simple but brutal—markets aren’t dangerous because of what happens often, but because of what happens rarely, and those extremes are exactly where this model focuses.


Reference:
Das, S. (2025). Predicting Stock Market Crash with Bayesian Generalised Pareto Regression
