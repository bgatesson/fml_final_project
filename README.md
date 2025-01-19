# Bitcoin Sentiment Analysis Project

This repository contains files related to Bitcoin sentiment analysis and price data:

## Data Files

- `bitcoin_data.csv`: Historical Bitcoin price data with dates and prices
- `bitcoin_sentiments_21_24.csv`: Raw sentiment data including dates, descriptions, sentiment scores and categories
- `bitcoin_sentiments_21_24_cleaned.csv`: Cleaned version of the sentiment data with processed descriptions
- `bitcoin_sentiments_21_24_cleaned_benchmarked.csv`: Sentiment data with benchmark predictions added
- `finetuned_finbert_preds_2.csv`: Optimized FinBERT sentiment predictions 
- `lstm_from_scratch_preds`: LSTM from scratch predictions


## Notebooks

- `data_cleaning.ipynb`: Notebook for cleaning and preprocessing the raw sentiment data
- `lstm_from_scratch_training.ipynb`: Training the LSTM model from scratch
- `finebert_finetuning.ipynb`: Finetuning the FineBERT model
- `return_modelling_using_sentiment.ipynb`: Modelling the return of Bitcoin using sentiment data (Part 2 of our project)

## Data Description

The sentiment data categorizes Bitcoin-related news and events into three sentiment categories:
- 0: Positive sentiment
- 1: Negative sentiment  
- 2: Neutral sentiment

The data spans from late 2021 to early 2024 and includes both price movements and market sentiment analysis.

