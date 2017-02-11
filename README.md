# superlearning-senti-analytics
# Supervised Learning Techniques for Sentiment Analytics

The goal of this project is to classify tweets and movie reviews as either positive or negative. For classification, the project uses logistic regression as well as a Naive Bayes classifier from python’s machine learning package scikit-learn.

A major part of this project is the task of generating feature vectors for use in these classifiers. It explores two methods:

1. A more traditional NLP technique where the features are simply “important” words and the feature vectors are simple binary vectors.
2. The Doc2Vec technique where document vectors are learned via artificial neural networks.

More documentation can be found in this repository for additional reading.

# Datasets
The IMDB reviews and tweets can be found in the data folder. These have already been divided into train and test sets.

* The IMDB dataset contains 50,000 reviews split evenly into 25k train and 25k test sets. Overall, there are 25k positive and 25k negative reviews. In the labeled train/test sets, a negative review has a score <= 4 out of 10, and a positive review has a score >= 7 out of 10. Thus reviews with more neutral ratings are not included in the train/test sets.
* The Twitter dataset contains 900,000 classified tweets split into 750k train and 150k test sets. The overall distribution of labels is balanced (450k positive and 450k negative).

# Data Source:
1. IMDB Dataset: http://ai.stanford.edu/~amaas/data/sentiment/
2. Twitter Datset: http://thinknook.com/twitter-sentiment-analysis-training-corpus-dataset-2012-09-22/

# Additional Resources:
1. https://districtdatalabs.silvrback.com/modern-methods-for-sentiment-analysis
2. https://radimrehurek.com/gensim/models/doc2vec.html
3. https://rare-technologies.com/doc2vec-tutorial/
