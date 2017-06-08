# Twitter-sentiment-analysis

This project involves taking up of dataset which includes tweets from different people on apple products.
Here the Variable we are trying to predict is the variable “Negative” That if the tweet is negative about apple or not.
As the tweets are in natural language they need to be preprocessed so that they can be used efficiently in the model therefore 
•	A corpus document is created of the CSV so that this corpus can be used for stemming to remove the unnecessary information from the corpus.
•	Corpus is processed to lower case, removing punctuations and remove stop words of English language.
•	A frequency matric is constructed to know about the occurrences of negative words.
•	To make the model a better one which can fit properly the sparse nature is removed by keeping only the terms that appear in 2% or more of the tweets.
•	Then lastly a CART model and Random forest model is constructed using the processed corpus document and the accuracy is compared with a baseline which always predicts the negative outcome.    














