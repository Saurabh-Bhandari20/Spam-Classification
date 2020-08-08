# Spam-Classification

Spam Classifiaction  is an important feature for the mail services because it hepls the user to only read or intercept messages that are important for the user.

In this project,
First I have created a word cloud for ham and spam messages.
Then i have created a new feature by removing stopwords, punctuations and i have also used stemming to change the words into their root words.
After that applying train test split on new feature and the label column with 85% of training and 15% of testing data.
After that i have used countvectorizer + tdidftransformer(which is equivalent to the tfidfvectorizer) for feature extraction.
And then applying three classification algorithms :
1.Support Vector machine
2.Logistic Regression
3.Multinomial Naive Bayes
and finding the appropriate algorithm 
Using Grid Search CV for Hyperparameter Tuning on Support Vector Machine for the best Parameters.
Then created a model using the joblib library that can be further used.
And for user input data, I have used python tkinter library for the GUI of the program which will predict whether the email is a Ham or Spam.

