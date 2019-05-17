# Sentiment Analysis on IT Service Desk

This repository contains three iPython notebooks to demostrate how to apply sentiment analysis with deep learning technology using Keras libraries.  It follows the same procedures that is used in [O'Reilly tutorial](https://www.oreilly.com/learning/perform-sentiment-analysis-with-lstms-using-tensorflow) on sentiment analysis with LSTMs in Tensorflow. The training data can be downloaded from https://github.com/adeshpande3/LSTM-Sentiment-Analysis or from http://ai.stanford.edu/~amaas/data/sentiment/

The three iPython notebooks are:
1) Preprocess_Docs_IMDB.ipynb - Load IMDB data (or your own labelled docs) to create word dictionary and encode all docs. 
2) Sentiment_Training_with_IMDB.ipynb - Use encoded matrics to train sentiment classifier with LSTM network. It contains MLP and CNN   algorithms for comparison purpose.
3) Process_IT_Tickets.ipynb - Apply the trained model to IT Service Desk sample data to get sentiment classification. You can use your owd data to perfrom this task.

## Requirements and Installation
In order to run these notebooks, you'll need the following libraries.


* **[TensorFlow](https://www.tensorflow.org/install/) version 1.1 or later**
* [Keras](https://keras.io/#installation)
* [NumPy](https://docs.scipy.org/doc/numpy/user/install.html)
* [Jupyter](https://jupyter.readthedocs.io/en/latest/install.html)
* [matplotlib](https://matplotlib.org/)

