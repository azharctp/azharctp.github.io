---
title: "Twitter sentiment analysis"
excerpt: "Twitter sentiment analysis based on 10000 tweets to determine the emotional tone behind the tweets.<br/><img src='/images/twitter_analysis.png'>"
collection: projects
---

A Twitter sentiment analysis is used to determine the emotional tone behind the tweets. This automated analysis tool can be utilized to understand the customer's perspective and the data can be useful in marketing. The corporates can target the tweets containing their product or brand names to get feedback using this technique.

**Training and test accuracies at the end of training.**

Train accuracy at the end of training= 0.9932 \
Test accuracy = 0.9932

**Training and test accuracies at the end of training after removing 5 emoticons**

Training accuracy at the end after removing emoticons = 0.7284 \
Test accuracy after removing emoticons = 0.6892

Both test and training accuracies were reduced once the 5 emoticons were removed. This is due to the high weightage given to the emoticons while labeling the dataset. The emoticons are a kind of direct representation of the kind of tweet compared to individual word counts and removing them from the model training resulted in a defective model.

The codes are available [here](https://github.com/azharctp/data-science-project/tree/main/Twitter_sentiment_analysis)
