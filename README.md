# Reddit Option Sentiment Bot

A Python bot that scrapes posts from **r/options**, extracts **stock tickers**, analyzes **sentiment using FinBERT**, and sends **Buy/Sell alerts** via **Pushbullet**.

## Features

- ✅ Scrapes Reddit using PRAW
- ✅ Detects stock tickers via regex
- ✅ Uses **FinBERT** for financial sentiment analysis
- ✅ Sends alerts when sentiment is strongly positive or negative (PushBullet and extended to Email)

## ML/NLP Focus

- FinBERT transformer for domain-specific sentiment
- Regex-based entity extraction (tickers only)
- Threshold-based signal classification

## 📁 Structure
main.py 
config.py
utils/ 
  ├── reddit_scraper.py 
  ├── sentiment_analyzer.py 
  ├── reddit_option_extractor.py 
  └── notifications.py
  
## Future Improvements

- Fine-tune FinBERT on Reddit finance data
- Aggregate sentiment by stock symbol
- Integrate market data (Yahoo Finance API)
- Deploy with scheduling + Streamlit dashboard



