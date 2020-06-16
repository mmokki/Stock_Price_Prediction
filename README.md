# Stock Price Movement Prediction
This is a group project. Team members are Jing Li, Jacqueline Huang, Paridhi Agal.

### GOAL
The goal of this project is to predict stock price movement of Tesla using relevant tweets and news.

### Data Source
- Tweets: Webscraped from Twitter
- News: Webscraped from Nasdaq news search result page
- Stock Price: Downloaded from YahooFinance

### Analysis
The analysis used two different textual representations, Word2vec for tweets and Doc2Vec for news articles. Our team applied sentiment analysis and supervised machine learning model to predict stock price movement for Tesla.

We did principal component reduction on the Word2Vec embedding for tweets. We predicted the direction of stock market movements for the next day (will it rise or fall?) and the percent change bracket for the next day as well. Our assumption is that positive news and tweets in social media about a company would encourage people to invest in the stock, and as a result the stock price of that company would increase.

### Result
Our prediction models based on tweets and news separately both have an accuracy of around 60%, based on combination of both news and tweets has an accuracy of 54%. In addition, we made time series model for stock price movement which had 90%+ accuracy and treated them as a benchmark. 

We observed that COVID 19 has negatively affected the model performance. It would perform much better when economic gets back to normal. We have also shared how the analysis can be extended for other use cases.
