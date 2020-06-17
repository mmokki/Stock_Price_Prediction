# Stock Price Movement Prediction
This is a group project. Team members are Jing Li, Jacqueline Huang, Paridhi Agal.


### Goal
The goal of this project is to predict stock price movement of Tesla using relevant tweets and news.


### Data Source
- [Twitter](https://twitter.com/search?q=tesla&src=typed_query)
- [Nasdaq News](https://www.nasdaq.com/search?q=tesla&page=1&sort_by=relevant)
- [Yahoo Finance](https://finance.yahoo.com/quote/TSLA?p=TSLA&.tsrc=fin-srch)


### Analysis
![Word2Vec Tweets Word Chart](https://github.com/mmokki/Stock_Price_Prediction/blob/master/Plots/Word2Vec%20Tweets%20Word%20Chart.png)

The analysis used two different textual representations, Word2vec for tweets and Doc2Vec for news articles. Our team applied sentiment analysis and supervised machine learning model to predict stock price movement for Tesla.

We did principal component reduction on the Word2Vec embedding for tweets. We predicted the direction of stock market movements for the next day (will it rise or fall?) and the percent change bracket for the next day as well. Our assumption is that positive news and tweets in social media about a company would encourage people to invest in the stock, and as a result the stock price of that company would increase.


### Result
Our prediction models based on tweets and news separately both have an accuracy of around 60%, based on combination of both news and tweets has an accuracy of 54%. In addition, we made time series model for stock price movement which had 90%+ accuracy and treated them as a benchmark. 

We observed that COVID 19 has negatively affected the model performance. It would perform much better when economic gets back to normal. We have also shared how the analysis can be extended for other use cases.
