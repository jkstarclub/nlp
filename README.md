# nlp

First, read in the SMS Spam Collection data. Make two lists:

a) A list that contains the category of the SMS (ham or spam),
b) A list that contains the text of the SMS. Try to put it into all lowercase and filter out punctuation marks.

Split the data into a train and a test dataset.

Use sklearn.feature_extraction.text.

CountVectorizer to vectorize the training and test texts. 

Do not forget to use the words in the training set as a vocabulary for vectorization.

Save the vectorized training and test data along with the labels.

Train a MultinomialNB classifier based on the training data.

Save your classifier on Google Drive using the joblib package.

Start a new code cell, load your saved model and evaluate it by using sklearn.metrics.classification_report.
