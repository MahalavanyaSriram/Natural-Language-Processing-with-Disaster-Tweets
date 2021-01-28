# Natural-Language-Processing-with-Disaster-Tweets

## Abstract
With today’s technology, each person’s online footprint opens the door for a large treasure trove of information that can be used for many purposes that varies from analyzing market trends to understanding the general emotion of a group of people. Twitter data is especially very useful for a variety of purposes when it comes to the latter use case, mainly because there are more than 6000 new tweets every second. With the advancement of technology and Natural Language Processing methodologies, the process of text and sentiment analysis has become much easier than a few years earlier. If in case, a person tweets a message which was about an emergency or an impending disaster and this was recognized immediately by our NLP models, we would be able to react quicker than normal which would help save lives. This is pretty much the crux of our project. The main aim of our project is to distinguish if a tweet talks about a real disaster or not. This is for a competition hosted by Kaggle and the dataset provided consists of a training set of 10,000 hand classified tweets on which we built our models. For the purpose of identifying if a tweet is pertaining to a disaster or not, we tried out a variety of different models like bag of words, TF-IDF features, count vectorizer followed by a ridge classifier, a naive bayes approach, SVM and LSTM models, GloVe vectorization, BERT and k-fold cross validation on our BERT model. Out of all these, we found that the BERT model with a K-fold cross validation worked best for this dataset and gave us an f1 score of 0.83573.

## Dataset
https://www.kaggle.com/c/nlp-getting-started/data

## Data Pre-processing and Visulaization
The following were the steps we performed for understanding the data better
- Visualizations (Histograms, Bar charts , etc.)
- Embeddings/ Vectorisation (count vectors, TF-IDF vectorization , Continuous Bag of words, GloVe, Fasttext)
- Topic modelling (Latent Dirichlet allocation)
- Word Cloud
- Scatter text (a special type of interactive visualization)

## Implemenation Methods
- Simple Linear Classification - Logistic Regression
- A multinomial naïve-bayes
- Support Vector Machine
- Bidirectional LSTM
- BERT (Bidirectional Encoder Representations from Transformers)
- BERT + K- Fold Cross Validation
- Google Universal Encoder

## Take Away
We implemented many interesting things like scatter text, the BERT model. We tried different libraries and explored many new topics in NLP despite us being new to NLP.
We had fun!

## Note
To acsses or view HTML files please refer to https://htmlpreview.github.io/

 
