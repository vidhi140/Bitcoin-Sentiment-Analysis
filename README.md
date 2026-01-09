# Trader Sentiment Analysis

## Overview
This project analyzes the relationship between Bitcoin market sentiment (Fear/Greed) and trader performance using Hyperliquid historical data.  
The goal is to uncover patterns in trading behavior and provide actionable strategies based on market sentiment.

## Datasets
- `data/hyperliquid_trades.csv` : Historical trader transactions
- `data/fear_greed.csv` : Bitcoin Market Sentiment (Fear/Greed)

## Project Steps
1. **Data Cleaning**: Convert timestamps, handle missing values, and prepare date columns.
2. **Data Merge**: Combine trade data with market sentiment by date.
3. **Exploratory Data Analysis (EDA)**: Analyze PnL, win rates, leverage, and trade frequency under Fear vs Greed markets.
4. **Visualizations**: Charts to highlight trends and insights.
5. **Account-Level Analysis**: Identify top-performing and consistent traders.
6. **Key Insights**: Summarize findings and behavioral patterns.
7. **Actionable Strategies**: Recommend sentiment-aware trading strategies.
