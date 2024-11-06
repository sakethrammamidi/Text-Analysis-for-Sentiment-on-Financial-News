# Text-Analysis-for-Sentiment-on-Financial-News

Sentiment Analysis and Stock Price Correlation

Project Overview

This project aims to understand if the mood of news articles about companies affects their stock prices. The idea is to check whether positive news leads to stock prices going up, and negative news leads to stock prices going down. We will analyze the sentiment of news articles and compare it to the stock prices for the same day.

How Does It Work?

Collect News Articles:
We gather the latest news articles using RSS feeds from reliable news websites like Reuters and BBC.
This helps us get real-time news about companies.

Sentiment Analysis:
We analyze the mood of the news articles: Is it positive, negative, or neutral?

For this, we use tools like:
VADER: A tool that works well for social media and news.
TextBlob: A simple tool to detect sentiment.
HuggingFace Transformers: An advanced tool using machine learning to understand text.
Get Stock Prices:

We use Yahoo Finance to get stock prices for the companies mentioned in the news articles.
We collect the stock prices for the same day each article was published.

Match News and Stock Data:
We match the sentiment of each article with the stock price on the same day.
This creates a table that shows whether positive or negative news matches stock price changes.
Analyze and Visualize:

We create a scatter plot to show the relationship between news sentiment and stock prices.
The chart helps us see if there is a pattern: Does good news lead to rising stock prices? Does bad news lead to falling prices?

Libraries Used
feedparser: Used to fetch news articles from websites via RSS feeds.
newspaper3k: Helps process and extract the text from the news articles.
VADER: A sentiment analysis tool that helps determine if an article is positive or negative.
TextBlob: Another tool for analyzing sentiment in text.
HuggingFace Transformers: Uses advanced language models to analyze sentiment.
yfinance: Allows us to fetch stock prices for companies.
matplotlib & seaborn: Libraries to create visualizations like charts.

What You Will Get From This Project
Sentiment Data: Each news article is labeled as positive, negative, or neutral based on its content.
Stock Data: Stock prices for the companies mentioned in the news are collected for the same days the articles were published.
Visualization: A scatter plot that shows how the mood of news articles (positive or negative) relates to the stock price changes. This helps to see if there's any trend between the two.

Next Steps
Clone this repository and run the code on Google Colab to start fetching news and stock data.
Modify the list of companies or news sources to explore how different companies' news affects stock prices.
Improve sentiment analysis by testing different models or adding more complex data sources.
This project gives a simple view of how news sentiment might impact stock prices. It's a great starting point for exploring more complex topics in data science and finance.
