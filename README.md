# Inflation and Sector Volatility: A Quantitative Analysis of Consumer Staples vs. Discretionary Stocks

## Overview

This project investigates the asymmetric effects of inflation on two key equity sectors:
- **Consumer Discretionary (XLY)** — Non-essential goods
- **Consumer Staples (XLP)** — Essential goods

The main hypothesis:  
> During high inflation periods, **XLY becomes more volatile**, while **XLP becomes more stable**.

This behavior implies a potential trading strategy that **reallocates sector weights** based on inflation regimes.

## Key Insights

- **XLY volatility rises** during high inflation, while **XLP volatility drops**
- **XLP consistently shows lower volatility**, reinforcing its defensive nature
- Portfolio strategy:  
  - Prioritize **XLY** during stable/low inflation for growth  
  - Prioritize **XLP** during high inflation or deflation for stability

## Data Sources

- **ETFs:**
  - XLY (Consumer Discretionary)
  - XLP (Consumer Staples)  
  *(Source: Yahoo Finance via `yfinance`)*

- **Macroeconomic Indicators:**
  - CPI (Consumer Price Index)
  - UNRATE (Unemployment Rate)
  - RSAFS (Retail Sales)  
  *(Source: FRED via `pandas-datareader`)*

## Dependencies

Install required Python packages with:
```bash
pip install pandas matplotlib yfinance fredapi scikit-learn statsmodels pandas-datareader
