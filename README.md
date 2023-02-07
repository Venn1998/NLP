# NLP
Natural Language Processing projects.


## - Corona Fake News Classifier:

The purpose of this project is to discover characteristic features of fake news about Covid-19 using basic NLP tools. We will also see if it is possible to automatically classify fake news with machine learning methods.

We begin using a simple logistic regression model, trained only on the headlines, that reaches accuracy of 84% on the test set. We'll take advantage of the simplicity of the logistic regression model to infer what are the most informative features of fake news.

At the end we implement a more complex classifier, using a RNN with LSTM cells and a pretrained embedding layer (Glove). This model will be trained on the full bodies of the news. The accuracy of this model on the test set is comparable with the accuracy of the simpler logistic regression model and it takes much more time to train it. Moreover, being a deep learning model, it is opaque and we can't see what features the model uses to distinguish between fake and true news.


## - Sentiment Analysis

In this project I performed different tasks on textual data:

1. **Detection of opinion elements**: Identification of targets, aspects and opinion words from hotels reviews.
2. **Polarity detection**: Extraction of polarities from opinions, data was taken from twitter API using tweepy.
3. **Rating**: implementation of different ML models to classify reviews.
4. **Evaluation**: comparison of models.
