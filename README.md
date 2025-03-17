# CS6375_Assignment-1

This project explores the implementation and evaluation of neural networks for sentiment analysis on Yelp reviews. Specifically, I implemented and experimented with two types of neural networks: a Feedforward Neural Network (FFNN) and a Recurrent Neural Network (RNN). The task involves predicting the star rating (1-5) of a review based on its text content.
The dataset consists of Yelp reviews, with each review labeled with a rating from 1 to 5 stars. In the implementation, these ratings are one-indexed as 1-5. The data is divided into training, validation, and test sets.

For the FFNN implementation, I completed the forward pass method in the neural network class in ffnn.py file

For the RNN implementation, I completed the forward method to handle sequential input data in rnn.py file

Both ffnn and rnn models were evaluated using accuracy as the performance metric.

All these results are obtained by running the ffnn.py and rnn.py files with the required hyperparameters in the jupyter notebook results.ipynb. The results.ipynb notebook is also attached along with the report in the GitHub repo.

The predictions obtained by the ffnn model are saved as results in ffnn_results_1.csv, ffnn_results_2.csv, ffnn_results_3.csv for 32, 64 and 128 hidden layer dimensions respectively.

The predictions obtained by the rnn model are saved as results in rnn_results_1.csv, rnn_results_2.csv, rnn_results_3.csv for 32, 64 and 128 hidden layer dimensions respectively.
