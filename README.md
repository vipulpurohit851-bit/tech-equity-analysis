# Technology Sector Equity Analysis

## Overview
This project analyzes historical stock data from the Technology sector using:

- Apple (AAPL)
- Microsoft (MSFT)
- NVIDIA (NVDA)

## Objectives
- Identify patterns and anomalies
- Build a simple trading strategy
- Backtest the strategy
- Evaluate risks and limitations

## Key Findings

### Pattern 1: NVIDIA Outperformance
NVIDIA significantly outperformed Apple and Microsoft while showing higher volatility.

![Normalized Trend](normalized_trend.png)

---

### Pattern 2: Correlation Analysis
Technology stocks exhibited moderate positive correlation.

![Correlation Heatmap](correlation_heatmap.png)

---

### Pattern 3: Volatility Analysis
NVIDIA showed wider return distribution indicating greater volatility.

![Return Distribution](return_distribution.png)

---

## Trading Strategy

Moving Average Crossover Strategy

Buy:
- 20-day MA > 50-day MA

Sell:
- 20-day MA < 50-day MA

![Moving Average Strategy](moving_average_strategy.png)

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Yahoo Finance
- Jupyter Notebook
