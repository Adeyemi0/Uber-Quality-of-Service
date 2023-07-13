![Uber Eats!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/uber.jpg)
## Introduction
In today's highly competitive food delivery industry, it is crucial for companies like UberEats to maintain a high level of service quality to attract and retain customers. While businesses often promote their services through marketing campaigns, the real measure of their quality lies in the experiences and opinions of actual customers. By analyzing customer tweets about UberEats, we can gain valuable insights into the true service quality provided by the company.

## Objective:
The main objective of this project is to evaluate UberEats' service quality by analyzing customer tweets. By examining a large volume of unfiltered and unbiased customer opinions, we aim to uncover the strengths and weaknesses of UberEats' service, identify areas for improvement, and gain a comprehensive understanding of customer sentiment towards the company.

## Methodology
#### 1. Data Collection
In order to perform this analysis, the SNSCRAPE python library was used to get 8433 tweets. All results gathered from this analysis are from this dataset. The dataset was collected by searching for the keyword #ubereats. 
![Scaping Tweets!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/scrape.png)

#### 2. Data Preprocessing
The collected tweets undergo various preprocessing steps, such as removing special characters, URLs, and emojis, as well as tokenization and lemmatization.	This process helps to remove noise and irrelevant information from the text, making it easier to analyze the actual content of the tweets.

#### 3. Sentiment Analysis
I perform sentiment analysis on the preprocessed tweets using Natural Language Processing (NLP) techniques. This analysis helps me determine the overall sentiment of customers' tweets, whether positive, negative, or neutral.
![Sentiment Analysis!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/polarity_distribution.png)

#### 4. Emotion detection 
Emotion detection is performed on the cleaned text using the text2emotion library.
![Emotion Expressed!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/Emotions%20Expressed.png)

