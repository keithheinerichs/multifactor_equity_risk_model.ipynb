# multifactor_equity_risk_model.ipynb
Python implementation of a Fama-French five-factor equity risk model with security-level exposures, portfolio risk attribution, and rolling factor betas.


# Multi-Factor Equity Risk Model

## Overview

This project develops a quantitative equity risk model using the
Fama-French Five-Factor framework to analyze systematic and
idiosyncratic risk across a diversified U.S. equity portfolio.

## Objectives

- Estimate security-level factor exposures
- Measure portfolio systematic risk
- Evaluate abnormal returns (alpha)
- Analyze idiosyncratic volatility
- Track time-varying exposures using 60-day rolling regressions

## Factors

Mkt-RF — Market
SMB — Size
HML — Value
RMW — Profitability
CMA — Investment

## Investment Universe

AAPL
MSFT
NVDA
JPM
XOM
JNJ
PG
HD
CAT
KO

## Methodology

1. Download adjusted equity prices
2. Calculate daily returns
3. Import Fama-French factor data
4. Estimate OLS factor regressions
5. Analyze alpha and factor betas
6. Construct equal-weight portfolio
7. Estimate portfolio factor exposures
8. Calculate 60-day rolling betas
9. Decompose systematic and idiosyncratic risk


## Dashboard

[Insert dashboard image]

## Technologies

Python
Pandas
NumPy
Statsmodels
Matplotlib
yfinance
pandas-datareader


Historical factor exposures are not forecasts of future returns.
The model also excludes momentum, liquidity, macroeconomic,
and other potential systematic factors.
