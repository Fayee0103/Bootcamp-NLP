# Unit 12—Tales from the Crypto

![Stock Sentiment](Images/sentimental.jpeg)

## Background

There's been a lot of hype in the news lately about cryptocurrency, so you want to take stock, so to speak, of the latest news headlines regarding Bitcoin and Ethereum to get a better feel for the current public sentiment around each coin.

In this assignment, you will apply natural language processing to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. You will also apply fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

## Tasks

1. [Sentiment Analysis](#1---Sentiment-Analysis)
2. [Natural Language Processing](#2---Natural-Language-Processing)
3. [Named Entity Recognition](#3---Named-Entity-Recognition)

---

## Code

[crypto_sentiment](crypto_sentiment.ipynb)

---

## Instructions

### 1 - Sentiment Analysis

Use the [newsapi](https://newsapi.org/) to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.

Using descriptive statistics, findings are as below:

> Bitcoin had the highest mean positive score?
>  
> Bitcoin had the highest negative score?
>   
> Bitcoin had the highest positive score?



### 2 - Natural Language Processing

In this section, you will use NLTK and Python to tokenize text, find n-gram counts, and create word clouds for both coins. 
#### Technique used:
#### Tokenize

Be sure to:

1. Lowercase each word.
2. Remove punctuation.
3. Remove stop words.
4. Tokenize
5. N-grams (NLTK)
6. Word Clouds
7. Named Entity Recognition


#### Word Clouds



![btc-word-cloud.png](btc-word-cloud.png)

![eth-word-cloud.png](eth-word-cloud.png)

