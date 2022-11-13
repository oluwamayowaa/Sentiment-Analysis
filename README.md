# Twitter Sentiment Analysis

The main objective of this project was to scrape tweets mentioning the verified Airbnb twiiter account to determine sentiments of users.

Tweets were crawled using tweepy API and sentiment polarity was determined by feeding text data into Hugging Face's Twitter-roBERTa-base transformer model.

## Files

1. airbnb.csv contains scraped tweets.
2. clean_df contains cleaned tweets.
3. Sentiment_Analysis is the jupyter notebook file that contains the code.
