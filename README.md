# shariah-vs-conventional-portfolio
Quantitative risk-adjusted performance comparison of Shariah-compliant vs. conventional equity portfolios on the Pakistan Stock Exchange (PSX) using Python.
# Shariah-Compliant vs. Conventional Equity Portfolios: A Risk-Adjusted Performance Analysis

## Overview
Quantitative comparison of Shariah-compliant and conventional equity portfolios on the 
Pakistan Stock Exchange (PSX), evaluating the risk-return tradeoff of Islamic screening 
criteria across four matched sectors (Banking, Technology, Fertilizer, Cement).

# Methodology
- Constructed two baskets: Shariah-Compliant (MEBL, SYS, EFERT, LUCK) vs. Conventional 
  (HBL, TRG, FFBL, DGKC)
- Used 3 years of historical price data (2023–2025) via yfinance
- Computed annualized return, volatility, Sharpe Ratio, and 95% Value at Risk (VaR)
- Identified and corrected anomalous price data using return clipping

## Key Findings
- Conventional basket: higher average return (47.4%) and Sharpe Ratio (1.07)
- Shariah-Compliant basket: lower tail risk (95% VaR: -2.50% vs. -3.10%)

## Tools
Python (Pandas, NumPy, Matplotlib, yfinance), Google Colab

## Files
- `Shariah_vs_Conventional_Portfolio_Analysis.ipynb` — full analysis notebook
