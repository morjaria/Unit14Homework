# Unit14Homework
# LSTM Stock Predictor

![deep-learning.jpg](Images/deep-learning.jpg)

Due to the volatility of cryptocurrency speculation, investors will often try to incorporate sentiment from social media and news articles to help guide their trading strategies. One such indicator is the [Crypto Fear and Greed Index (FNG)](https://alternative.me/crypto/fear-and-greed-index/) which attempts to use a variety of data sources to produce a daily FNG value for cryptocurrency. You have been asked to help build and evaluate deep learning models using both the FNG values and simple closing prices to determine if the FNG indicator provides a better signal for cryptocurrencies than the normal closing price data.

Used deep learning recurrent neural networks to model bitcoin closing prices. One model  used the FNG indicators to predict the closing price while the second model  used a window of closing prices to predict the nth closing price.


## Submission Files

[Closing Prices  Notebook](submission/lstm_stock_predictor_closing.ipynb)

[FNG Starter Notebook](submission/lstm_stock_predictor_fng.ipynb)

### Data Files

[Data used] submission/data

### Evaluate the performance of each model

Finally, use the testing data to evaluate each model and compare the performance.

Use the above to answer the following:

> Which model has a lower loss?
* The model predicting  based on price performs better with a loss of 0.048721764236688614 while the FNG based model has a loss of 0.1911110132932663

> Which model tracks the actual values better over time?
The model predicting  based on price trackes actual values better than the FNG based one.
 

> Which window size works best for the model?