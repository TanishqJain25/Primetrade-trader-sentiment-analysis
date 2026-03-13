# Crypto Trader Sentiment Analysis

This project analyzes how cryptocurrency trader performance changes under different market sentiment regimes such as Fear, Greed, Extreme Greed, and Neutral.

## Objective
Understand the relationship between market sentiment and trader behavior using historical trading data and the Bitcoin Fear & Greed Index.

## Tools Used
Python  
Pandas  
Matplotlib  
Jupyter Notebook  

## Data Sources
1. Bitcoin Fear & Greed Index dataset  
2. Historical trader data from Hyperliquid  

## What Was Done
- Cleaned and aligned trader data with daily sentiment data
- Calculated daily trading metrics such as PnL, win rate, and trade count
- Merged sentiment classification with trader performance
- Segmented traders into frequent vs infrequent and consistent vs inconsistent groups
- Compared trading behavior across sentiment regimes

## Key Insights
- Traders performed best during **Neutral market sentiment**
- **Extreme Greed periods showed the highest trading activity**
- **Win rates declined during Fear periods**
- Frequent traders generally achieved **higher cumulative PnL**

## Visualizations
- PnL vs Market Sentiment
- Win Rate by Sentiment
- Trade Count Distribution
- Trader Segmentation Analysis

## Output
The notebook generates visualizations showing the relationship between market sentiment and trader performance, including PnL trends, win rates, and trading activity across sentiment regimes.

## Project Structure
analysis.ipynb  
README.md  
data/
    trader_data.csv
    fear_greed_index.csv

## How to Run
1. Open the Jupyter notebook  
2. Run all cells sequentially to reproduce the analysis

## Author

Tanishq Jain
