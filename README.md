# NLP_projects
This repo Contains all the NLP based projects Done by Milan Roat

## Stock Sentiment Analysis Using News Headlines
#### This project is a news sentiment and stock trend analysis system that extracts financial news headlines, processes them to identify market trends, and combines them with stock data to determine bullish or bearish patterns. It helps in predicting market sentiments and understanding stock performance based on news and historical trends.

#### Technologies/Libraries Used: Python, BeautifulSoup, TensorFlow/Keras, pandas, NumPy, and LSTM-based neural networks.

#### Key Steps:

1] News Scraping: Extract financial news headlines from Finviz for multiple stock tickers using BeautifulSoup.
2] Data Processing: Group and concatenate multiple news headlines by date for each stock ticker.
3] Sentiment Labeling: Combine stock price data with news headlines to label stock trends as bullish or bearish based on closing and opening prices.
4] Embedding and Tokenization: Convert text data into numerical format using Keras's Tokenizer and pad sequences for uniform input length.
5] Model Training: Train an LSTM-based neural network to predict sentiment trends from processed financial news data.
