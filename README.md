# Commodity-Linked Equities vs. the S&P 500

## Overview

This project examines how commodity-linked equities behave relative to the broader U.S. equity market.

The analysis compares two periods, 2016–2020 and 2021–2025, to investigate changes in market sensitivity and risk-adjusted performance.

## Assets

- Energy: XOM, COP
- Metals & Mining: FCX, NEM
- Agriculture: ADM
- Market benchmark: SPY

## Methods

- Daily returns
- Annualized arithmetic and geometric returns
- Annualized volatility
- Correlation with SPY
- CAPM regression
- Beta and alpha
- R² and coefficient significance
- Sharpe ratio

## Key Findings

- FCX displayed the highest market beta in both periods.
- Market sensitivity declined substantially for XOM, COP, and ADM in the
  2021–2025 period.
- SPY explained a smaller portion of return variation for several
  commodity-linked equities after 2020.
- Risk-adjusted performance differed substantially across firms and periods.

## Tools

Python, Pandas, NumPy, Matplotlib, Statsmodels, yfinance

## Limitations

The analysis uses SPY as the primary market factor and a simplified
risk-free-rate assumption. Future extensions could incorporate oil, gold,
and copper prices directly.
