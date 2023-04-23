# estimateBitcoin

## This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on the relation between Bitcoin price and tweets involving it
Please look at the Notebook provided to view the process and methodology behind our analysis

## Contributors
- @arifspidey - contributed in cleaning, exploratory analysis and machine learning
- @ronakpahwa - contibuted project idea, finding datasets, machine learning and presentation
- @apaditya7 - contributed machine learning, finding datasets and visualisation

## Problem definition
Are we able to estimate how a particular tweet can influence the price of Bitcoin?

## What did we learn from this project?
## Overview
In this project, we aimed to predict the price of Bitcoin using sentiment analysis of tweets. We collected data from the Kaushik Suresh's Bitcoin tweets dataset, cleaned the data, and performed exploratory data analysis to gain insights into the relationship between Bitcoin prices and tweet sentiment. We also used machine learning techniques, specifically linear regression, to predict the price of Bitcoin.

## Dataset
We obtained the dataset from Kaggle, which contains over 160,000 rows of tweets tweets related to Bitcoin. We cleaned the dataset by removing duplicates, null values, URLs, mentions, and stop words. We also performed sentiment analysis on the cleaned tweet text using VADER and obtained sentiment scores for each tweet.

## Exploratory Data Analysis
We explored the sentiment distribution in the dataset, identified commonly used words in positive and negative tweets, and established a weak positive correlation between sentiment scores and Bitcoin price and that the relationship between the two is highly complex.

## Machine Learning
We split the dataset into training and testing sets and used linear regression to predict the Bitcoin price based on sentiment scores. We used various performance metrics such as MSE, and R-squared to evaluate the model's performance. However, these models have their limitations, and their accuracy is affected by various factors such as data quality, model assumptions, and the complexity of the relationship between the variables.

## Tools Used
- Python 3.9
- Jupyter Notebooks
- VADER package
- Coinbase API

## Key Takeaways
- Data collection and cleaning are essential for any data science project. In this project, we had to deal with missing data, incorrect data types, and inconsistent data formats. We learned that carefully cleaning and pre-processing the data is critical to obtaining accurate insights and predictions
- We learned how to use VADER, a lexicon and rule-based sentiment analysis tool, to calculate the sentiment scores of tweets. VADER provides a quick and simple way to evaluate tweet sentiment, but it has its limitations, such as its inability to handle sarcasm and other forms of figurative language.
- The Bitcoin market is highly volatile, and predicting its price is a complex task. While our linear regression model showed some promise in predicting Bitcoin prices, its accuracy was not sufficient for practical use.

## Recommendations
Based on our analysis, we recommend the following:
- Further exploration of the relationship between tweet sentiment and Bitcoin prices using more advanced techniques such as neural networks and other machine learning algorithms.
- Consideration of additional factors such as news articles, social media posts, and economic indicators that may impact Bitcoin prices.
- Ongoing monitoring of the Bitcoin market and analysis of market trends to inform future predictions.

## Conclusion
This project demonstrates how sentiment analysis can be used to predict the price of Bitcoin based on Twitter data. The project also showcases various tools and techniques used in data science, such as cleaning data, performing exploratory analysis, and using machine learning models for prediction.
- Certain components of a tweet affect its influence, which can be positive or negative, based on the original sentiment of the tweet
- Influence has a weak correlation to price
- Bitcoin has many factors affecting its price
- Our project can be improved and expanded upon to fit other context

## References
- https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets
- https://www.kaggle.com/code/erdeq1024/bitcoin-price-analysis-by-tweets
- https://pypi.org/project/vaderSentiment/
- https://pypi.org/project/cbpro/


