# Stock_Price_Prediction
This project utilized tweets and Nasdaq news of Tesla to predict its stock price movement.

The present analysis has used two different textual representations, Word2vec for tweets and Doc2Vec for news articles for analyzing the public sentiments. Our team have applied sentiment analysis and supervised machine learning models to the text extracted from Twitter and Nasdaq news website.

We also did principal component reduction on the Word2Vec embedding for tweets. We tried to predict the direction of stock market movements for the next day, will it rise or fall and predict the percent change bracket for the next day. The idea is that positive news and tweets in social media about a company would definitely encourage people to invest in the stocks of that company and as a result the stock price of that company would increase.

Our prediction models based on tweets and news separately have an accuracy of 60%, based on combination of both news and tweets has an accuracy of 54%. We made time series models for stock price movement which had 90%+ accuracy and treated them as a benchmark. We have also shared how the analysis can be extended for other use cases.

### Data Source
- Tweets: Webscraped from Twitter
- News: Webscraped from Nasdaq news search result page
- Stock Price: Downloaded from YahooFinance
