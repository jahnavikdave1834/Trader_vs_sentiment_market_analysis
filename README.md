# Trader Performance vs Bitcoin Market Sentiment

This project analyzes the relationship between Bitcoin market sentiment and trader performance using historical trading data from the Hyperliquid exchange and the Bitcoin Fear & Greed Index.

## Objective
To understand how market sentiment (Fear, Greed, Neutral) affects trader behavior, profitability, and trading activity.

## Dataset
Two datasets were used:
- Hyperliquid historical trading data
- Bitcoin Fear & Greed Index

## Methodology
1. Load and clean both datasets.
2. Convert timestamps and align data by date.
3. Merge trading data with market sentiment data.
4. Perform exploratory data analysis.
5. Visualize trader performance under different sentiment conditions.

## Key Insights
- Trading activity is highest during Fear periods.
- Average profit per trade is highest during Greed markets.
- Traders tend to sell more during Greed sentiment, indicating profit-taking behavior.

## Tools Used
- Python
- Pandas
- Matplotlib
- Google Colab
