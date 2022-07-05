# Next Word Prediction_Deep Learning

## In our multi-class classification problem we will learn the relationships among our words and then provide probabilities as to which word should be next in our sequence. The model can only provide probabilities for words it has seen. We have used n_gram sequences and word embeddings to assist our model in learning the relationship between the words.

1)	Dataset downloaded from 80s songs | Kaggle
2)	Glove 6B.50. Retrieved from GloVe: Global Vectors for Word Representation (stanford.edu)
3)  For this project i run python 3.7.13 on Google Colab

This was my first Deep Learning Assignment and I choose to practice on NLP and more precisely on Next Word Prediction. The model tries to predict the next lyrics implementing LSTM. 

I choose not to follow the recommended path; instead of Keras Embeddings used Glove 50 dimensions and used n-grams to find the set of co-occuring words. 

In the future I would like to have the CPU needed to run more epochs in order to see better results.
