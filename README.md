# Spam-or-Ham-NLP
The SMS Spam Collection is a set of SMS tagged messages that have been collected for SMS Spam research. It contains one set of SMS messages in English of 5,574 messages, tagged according to being ham (legitimate) or spam.
Things to be  done:

a)Download the file and set it as a Dataframe. 

b)Remove punctuations, special characters and stopwords from the text in ‘sms’ column. Convert the text to lower case.

c)Create two objects X and y. create a CountVectorizer object and split the data into training and testing sets. Train a MultinomialNB model and Display the confusion Matrix 

d)Display the POS tagging on the first 4 rows of ‘sms’.

e)Build and display a dependency parser tree for the sentence :

  “the series opened 17 years later, as Viserys Targaryen tried to win an eastern tribal army to his side, so he could retake the Iron Throne” 


Data: https://www.kaggle.com/uciml/sms-spam-collection-dataset/download
