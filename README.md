![Scaping Tweets!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/uber.png)

# Table of Contents
1. [Objective](#objective)
2. [Methodology](#methodology)
   - [Data Collection](#1-data-collection)
   - [Data Preprocessing](#2-data-preprocessing)
   - [Sentiment Analysis](#3-sentiment-analysis)
   - [Emotion Detection](#4-emotion-detection)
   - [Complaint Classification](#5-complaint-classification)
   - [Hashtag Analysis](#6-hashtag-analysis)
   - [WordCloud](#7-wordcloud)
   - [Engagement Rate](#8-engagement-rate)
3. [Recommendation](#recommendation)

## Objective
The main objective of this project is to evaluate UberEats' service quality by analyzing customer tweets. By examining a large volume of unfiltered and unbiased customer opinions, I aim to uncover the strengths and weaknesses of UberEats' service, identify areas for improvement, and gain a comprehensive understanding of customer sentiment towards the company.

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
Emotion detection is performed on the cleaned text using the text2emotion library. Emotion detection aims to identify the predominant emotions expressed in the tweets. The library assigns emotion labels to the text, such as happy, sad, angry, surprised, or neutral, based on the detected emotions. Analyzing emotions helps understand the emotional response and sentiment conveyed by the Twitter users.
![Emotion Expressed!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/Emotions%20Expressed.png)

#### 5. Complaint Classification
To find common food delivery complaints related to late delivery, wrong delivery, driver, cancelled order, unfair charges. I searched for keywords like 'cost', 'charged','fee','price','refund','afford','deduct','deducted','pay', 'wait', 'waiting', 'waited','long','delay','delayed','cancel', 'cancelled','void','voided',
'wrong', 'incorrect','address','mix-up','mix up','care', 'assistance','complaint','hotline','support','service','driver', 'professionalism','guy'. These keywords are searched in the substring of individual tweets. 


![Complaint Classification!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/word_count_bar_chart.png)

Complaint Classification involves categorizing tweets into specific problem categories (late delivery, wrong delivery, driver, cancelled order, unfair charges, and others) based on these predefined keywords. If a tweet does not match any predefined keyword, it is categorized as "others". Categorizing unmatched tweets as "others" ensures that all tweets are accounted for, even if they do not fall into any specific problem category

![Frequency of problem!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/Frequency%20of%20Problems.png)

#### 6. Hashtag
Interestingly, some of the hashtags used are used in reference to Uber eats competitors. Others are related to food, cupcakes, and pumpkin spice. It is safe to assume most Uber eats customers sell or buy these foods. 

![Hashtag!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/hashtags.png)

#### 7. WordCloud
The WordCloud is  utilized to analyze customer complaints related to UberEats by visualizing the frequency of words used in their tweets. By presenting a visually compelling representation of the most common words or topics in the data, it offers a swift and intuitive overview of the key concerns expressed by customers.

![Cancelled order!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/wordcloud_Cancelled%20Order.png)

![Customer Service!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/wordcloud_Customer%20Service.png)

![Driver!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/wordcloud_Driver.png)

![Charges!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/wordcloud_Fee%20or%20charges.png)

![Late Delivery!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/wordcloud_Late%20delivery.png)

![Wrong Delivery!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/wordcloud_Wrong%20delivery.png)

![Other!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/wordcloud_other.png)

#### 8. Engagement Rate
The engagement rate by customer complaint refers to the level of interaction and response generated by customers' complaints on social media platforms, specifically in this case, regarding UberEats. It is a measure of the extent to which customers' complaints have captured the attention and engagement of other users.
![Engagement Rate!](https://github.com/Adeyemi0/Uber-Quality-of-Service/blob/main/pictures/Engagement%20Rate%20per%20segments.png)

## Recommendation
Based on these findings, the following recommendations can be made:

1. Improve Driver Performance: UberEats should focus on driver training and monitoring to address concerns related to driver behavior, professionalism, and reliability.

2. Enhance Communication and Support: Efforts should be made to improve customer service channels, response times, and overall communication to address customer concerns promptly and effectively.

3. Transparent Pricing and Fee Structure: UberEats should ensure transparency and clarity in their pricing and fee structure, addressing customer concerns regarding cost, refunds, and credits.

4. Timely Deliveries: Efforts should be made to minimize late deliveries and provide accurate delivery estimates to meet customer expectations and reduce waiting times.

5. Continuous Improvement: UberEats should closely monitor customer feedback, sentiment, and keyword frequencies to identify emerging trends and areas for improvement. Regularly analyzing and addressing customer concerns will help enhance the overall service quality and customer experience.

By addressing these recommendations, UberEats can work towards meeting customer expectations, improving customer satisfaction, and maintaining a positive brand perception among its user base.
