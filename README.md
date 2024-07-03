# IMDB Reviews Sentiment Analysis
The aim of the analysis was to test the NLTK library for its sentiment analysis capabilities on the IMDB Reviews dataset.

**https://www.kaggle.com/code/daiton/imdb-reviews-sentiment-analysis**

## Description
The aim of this work was to test the NLTK library and its capabilities for sentiment analysis on a selected dataset of reviews from the IMDB platform. The output of the work is a detailed analysis of three main approaches to sentiment analysis using NLTK and other supporting libraries.

## Results
Weaker accuracy (around 65%) was achieved for the dictionary methods, balanced by a fast and simple implementation. Within the naive Bayes, logistic regression and SVM classifiers, quite polarizing results were obtained, which varied considerably according to the way the features were represented. Linear classifiers with a unigram or bigram model of word representation performed best, with around 80% accuracy or more. For trigrams and embedding vectors, a significant drop in accuracy was found, mainly due to the nature of the data. In this case, the correctnesses had quite a large variance between values of 50% and 75% correct. The last model to be trained was the pre-trained BERT model, which achieved 90% correct after an hour of training and can be considered the best result in terms of accuracy.

## Authors
* David Poslušný
