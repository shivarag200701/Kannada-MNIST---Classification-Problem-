# Toxic-Tweets-Classification-using-LSTM

A project made to analyze a CSV dataset obtained from Kaggle containing tweets classified tweets on the basis of toxicity.
Steps taken to solve the problem:
1. Cleaning data by removing non-ascii characters, special characters, etc. 
2. Employing stemming and removing stop words and omissions.
3. Converting the text to bag of words and Tfidf for further analysis.
4. Reducing the number of features by eliminating the least repeating words in the whole document.
5. This was followed by training 5 different classical machine learning models and checking their accuracy with the test data.

The five machine learning models used were:
 - Decision Trees
 - Random forest
 - Naive Bayes Model
 - K-NN Classifier
 - SVM

 It was an attempt to learn about Natural Language Processing and using certain libraries such as sklearn and re

Link to data: https://www.kaggle.com/datasets/ashwiniyer176/toxic-tweets-datasethttps://www.kaggle.com/competitions/jigsaw-toxic-comment-classification-challenge/data
