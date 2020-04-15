# Predicting Stock price of Apple using LSTM model

This is a final project for STAT 453: Deep Learning (Spring 2020), and its goal is to demonstrate how deep learning algorithm could be applied to the real world.

## Description

In this repository:
* Apple Stock Price LSTM: A LSTM model which predicts the daily prices of Apple's stock.
* apple.csv: A stock price data in csv format which includes the data of 10 years ranging from 1/4/2010 to 4/9/2020

### Libraries

The code was written in Python 3 using jupyter notebook with:
* Pandas and Numpy (Data Manipulation)
* Matplotlib (Visualisation)
* Keras (Building and Training the model)
* sklearn (Scaling the data)

## Conclusion

While the model displays extremely low MSE in all Train/Validation/Test sets. It is very risky to make an invest decision based on the model, as the prediction are not highly precise and accurate. Since there are numerous externalities that affects the stock price, LSTM neural network is not capable of predicting the stock price solely based on the past stock prices.
