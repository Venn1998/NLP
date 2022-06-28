Coronavirus Fake News

Analysis and processing of textual information

- Get data from text
- Topic detection
- Text classification

The purpose of this project is to discover characteristic features of fake news about Covid-19 using basic NLP tools. We will also see if it is possible to automatically classify fake news with machine learning methods. We will use the <i>corona_fake.csv</i> dataset. This dataset contains news in English about covid-19 tagged according to whether it is <i>fake</i> news or not. The dataset is organized into four columns: title, text, source, label.

We begin using a simple logistic regression model, trained only on the headlines, that reaches accuracy of 84% on the test set. We'll take advantage of the simplicity of the logistic regression model to infer what are the most informative features of fake news.

At the end we implement a more complex classifier, using a RNN with LSTM cells and a pretrained embedding layer (Glove). This model will be trained on the full bodies of the news. The accuracy of this model on the test set is comparable with the accuracy of the simpler logistic regression model and it takes much more time to train it. Moreover, being a deep learning model is opaque and we can't see what features the model uses to distinguish between fake and true news.
