## NLP Sentiment analysis


#### Context:

This project performs sentiment analysis on a dataset of movie reviews. The goal is to classify each review as either positive or negative based on its text content.

#### Dataset
The dataset used in this project is the Large Movie Review Dataset taken from kaggle ( Datasetlink: https://www.kaggle.com/datasets/columbine/imdb-dataset-sentiment-analysis-in-csv-format) .Dataset contains two columns (text : the review of the movie and label : the sentiment label of the movie review).The dataset includes 40,000 movie reviews. Each review is labeled as either 1 (positive) or 0 (negative).

#### Preprocessing
The review texts are preprocessed using the Natural Language Toolkit (NLTK) library in Python. The preprocessing steps include tokenization, stop word removal, stemming, and lemmatization.

#### Model
The sentiment analysis model used in this project is a MultiNomial Naive Bayes classifier trained on the preprocessed review texts. The MultinomialNB classifier is implemented using the scikit-learn library in Python.

#### Results
The MultinomialNB classifier achieves an accuracy of 85.5% on the test set of the IMDb dataset, indicating that it can accurately classify movie reviews as positive or negative based on their text content.
