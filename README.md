# Twitter Sentiment Analysis and Time Series Forecast

## Description

This project aims to analyze a large dataset gleaned from the twitter API. The dataset named “ProjectTweets.csv” contains a collection of tweets that will be used for sentiment analysis and time series forecasting.

## Context

This dataset contains 1,600,000 tweets extracted using the twitter API.
It contains the following 5 fields:

1. ids: The id of the tweet (eg. 4587).
2. date: the date of the tweet (eg. Sat May 16 23:58:44 UTC 2009).
3. flag: The query (eg. lyx). If there is no query, then this value is NO_QUERY.
4. user: the user that tweeted (eg. bobthebuilder).
5. text: the text of the tweet (eg. Lyx is cool).

## Ojectives

1. Utilisation of Hadoop and Spark for storage and distributed data processing environment.
2. Perform a comprehensive analysis of the pre-processed dataset, extracting relevant information and insights from the tweets.
3. Conduct sentiment analysis to determine the sentiment (positive, negative, or neutral) expressed in the tweets.
4. Develop a time series forecast of the sentiment for the entire dataset, predicting sentiment trends at 1 week, 2 weeks and 3 weeks using ARMA, ARIMA and SARIMAX.
5. Present the sentiment forecast as a dynamic dashboard for easy visualisation and interpretation using Holoviz libraries in jupyter notebook.
