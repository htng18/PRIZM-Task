# PRIZM Task

# This folder contains the code and data set for PRIZM texting mining task

# Data set contains two sets of data which are
# 1. train_set.csv
# 2. test_set.csv
# train_set.csv contains a set of news and their categories 
# There are three categories.
# test-set.csv contains a set of news without label.

# Gaol: Set up a model for classifying the news accordingly
# Outline of basic procedure:
# 1. Load the data set, train_set.csv, using into a dataframe
# 2. Clean the data set by removing alphabet,digit, symbols and stopwords.
# 3. Use jieba to tokenize the text into "words"
# 4. Split a part of data from train set for validation
# 5. Extract the feature from text using CountVectorizer (sklearn package)
# 6. Use the Naives Bayes model to train the data. 
# 7. Compute the accuracy score. 
# 8. Use the model for predicting the given data set.
