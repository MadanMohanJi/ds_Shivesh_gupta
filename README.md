Data Science Assignment - Web3 Trading Team
Candidate Information
Name: Shivesh Gupta

Colab Link: Click here to view Colab Notebook
Direct URL: https://colab.research.google.com/drive/1mDGfrF19l6SBPYOFVs-qBwfud4xXwVEF?usp=sharing

Project Overview
This project analyzes the correlation between Bitcoin market sentiment (Fear & Greed Index) and historical trader behavior on the Hyperliquid exchange. The goal is to identify if trading against the crowd ("Contrarian Strategy") yields higher profitability than following the trend.

Directory Structure
The repository is organized as follows:

notebook_1.ipynb: The primary analysis notebook containing all data fetching, cleaning, and visualization code.

ds_report.pdf: A formal summary of findings, including strategy performance metrics and visual evidence.

csv_files/:

hyperliquid_trader_data.csv: Raw transaction data.

fear_greed_index.csv: Daily sentiment classification.

processed_analysis_data.csv: The cleaned and merged dataset used for the final analysis.

outputs/:

strategy_performance.png: Boxplot showing PnL distribution by strategy.

size_usd_vs_sentiment.png: Bar chart showing average trade size (risk) per sentiment.

Setup & Instructions
Open the Colab Link provided above.

The notebook is self-contained and uses gdown to fetch datasets directly from Google Drive.

Run all cells sequentially to reproduce the analysis and generate the graphs found in the outputs/ folder.

Key Insights
Contrarian Signal: Shorting during "Greed" periods was identified as the most profitable strategy (Mean PnL: ~$85).

Risk Behavior: Traders tend to increase position sizes (USD) during extreme sentiment periods.
