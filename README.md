## Description
Created model for predicting the sentiment of the tweet.
Saved the model and used flask framework to make predictions.
Everytime user searches something in UI, it actually gets related tweets from the twitter using twitter API and then gives us the details about whether it is negative, positive or neutral speech.


This document explains how to get tweets from Twitter using the Twitter API in real-time and to create a model that can forecast whether a tweet is good, negative, or neutral. It also discusses the pre-processing and the GaussianNB model that was used to train the data.
Finally, it discusses how to utilize the Flask framework to build a user interface for interacting with the model and making predictions based on real-time tweets.


The data has been processed to liberate the tweets of these undesired characters by removing some patterns that are not alphabets and other unneeded characters.


 Lemmatization is similar to stemming but it brings context to the words. So Used Lemmatization to link words
with similar meanings to one word. 


## Creating a data model

The Naive Bayes machine learning model, which is inspired by the Bayes Theorem, is a simple but powerful probabilistic classification model. A conditional probability of an event A occurring given that event B has already occurred is provided by the Bayes theorem. When continuous predictor values that are predicted to follow a Gaussian distribution are present, the Gaussian Naive Bayes classifier is used.

The model was trained using both the bag of words and the tf-idf strategy since it was possible that the stop words in the bag of words approach had not been completely eliminated.

### Model based on tensor flow—LSTM
Words and their corresponding meanings are presented using embeddings. Similar to this, we are providing the maximum word count, the input word length, and the inputs from the preceding layer.

## using the produced model to download

The model that was trained in the preceding phase has been downloaded and stored from Colab so that it may be utilized with Flask and incorporated into the web.

## Model contrast
![alt](https://github.com/vinaykumarseelam/255_Bonus_2/blob/main/bonusComparison.png)






