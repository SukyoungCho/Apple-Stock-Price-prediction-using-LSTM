# Predicting Apple's Stock price using LSTM model

This is a final project for STAT 453: Deep Learning (Spring 2020), and its goal is to demonstrate how deep learning algorithm could be applied to the real world in making a profit.

In September 2019, Apple has become the world’s first trillion-dollar company. Apple’s stock price has escalated from 172 to 324 just in a year of 2019 – almost doubled. However, there are various factors, sometimes even imperceptible, affecting the stock price.

Therefore, the motivation of our project is to figure out whether machines are able to learn from the previous data and envisage profitable stocks. The development of technology may be more beneficial if people can make money without working but by investing with the help of AI. Since traditional neural networks have a major shortcoming in analyzing and predicting a trend of stock price, Long Short Term Memory networks, a special kind of Recurrent Neural Network, is adopted in order to loop through in themselves and generate accurate and precise prediction.

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
