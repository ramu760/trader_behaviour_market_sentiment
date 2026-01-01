# Trader Behavior Insights – Market Sentiment Analysis

## Overview
This project analyzes the relationship between **Bitcoin market sentiment (Fear & Greed Index)** and **trader performance** using historical trading data from Hyperliquid.

The goal is to understand how market sentiment influences:
- Trader profitability
- Win rates
- Trading behavior patterns

## Datasets Used
1. **Bitcoin Fear & Greed Index**
   - Date
   - Classification (Fear, Greed, Extreme Fear, Extreme Greed, Neutral)

2. **Historical Trader Data (Hyperliquid)**
   - Account
   - Coin
   - Execution Price
   - Size (Tokens & USD)
   - Side (Buy/Sell)
   - Timestamp
   - Closed PnL
   - Fees
   - Order & Transaction details

## Analysis Performed
- Data cleaning and timestamp alignment
- Merging trader data with daily sentiment
- Profitability analysis by sentiment
- Win rate comparison across sentiment types
- Distribution of trades under different sentiments

## Key Insights
- Greed and Extreme Greed periods show higher average PnL
- Win rates vary significantly with market sentiment
- Trader behavior changes noticeably during Fear vs Greed phases

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook

## Files
- `trader_sentiment_analysis.ipynb` – complete analysis notebook

## Author
Ramu Gutti
