# IMDBReviews
Sentiment Classification using Transformers, LSTM and Machine Learning

Sentiment Analysis is a classification of emotions (in this case, positive and negative) on text data using text analysis techniques (I use LSTM).

LSTM (Long Short-Term Memory) is one of the Recurrent Neural Network (RNN) architecture used in Deep Learning.

Keras is an open-source Python Deep Learning library, that could be run on Tensorflow back-end.

Dataset
In this work, I use 50.000 IMDB Movie Reviews from Kaggle. This dataset contains 2 columns, where the first column is the list of movie reviews and the second column is the list of sentiments (positive and negative). It is split equally between the positve and negative data.

Architecture
1. Embedding Layer
2. LSTM Layer
3. Dense (activation function using Sigmoid)
4. Optimizer: Adam, Loss Function: Binary Crossentropy

Machine Learning
1. TfIdfVectorizer
2. Random Forest
3. Confusion Matrix
