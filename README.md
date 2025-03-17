# Overview

This project estimates Value at Risk (VaR) using historical stock return data. While traditional parametric and Monte Carlo approaches assume normally distributed returns, this project highlights why financial returns often exhibit fat tails and asymmetry. To address these issues, a GARCH (Generalized Autoregressive Conditional Heteroskedasticity) model is used to estimate volatility and improve risk assessment.

# Features
1. Historical VaR Estimation: Uses past return distributions to compute risk.

2. GARCH Volatility Modeling: Accounts for time-varying variance to improve risk forecasting.

3. Comparison of Apple & Microsoft Stock Volatility: Demonstrates differences in risk profiles.

4. Data Sourcing from Yahoo Finance: Fetches real stock price data using yfinance.

5. Visualization & Analysis: Plots variance trends and distribution characteristics.

# Methodology

1. Data Collection: Retrieves stock price data from Yahoo Finance.

2. Return Calculation: Computes log returns to standardize volatility.

3. Historical VaR Estimation: Assumes future risk follows past return distribution.

4. GARCH Model Application: Predicts volatility for a 10-day horizon to estimate VaR.

5. Risk Interpretation: Analyzes how volatility affects investment decisions.

# Results

1. VaR estimates differ significantly when using historical data vs. normal assumptions.

2. GARCH-based VaR provides a more adaptive risk measure for volatile assets.

3. Apple's stock exhibits higher volatility than Microsoft's, affecting its risk profile.
