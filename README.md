# Crypto_price_prediction
**Overview**
Considering the volatility of Cryptocurrency, we have to determine tomorrow’s price of the cryptocurrency and  also next week price prediction. We have to use the classical Machine learning algorithms such as Linear Regression, Logistic Regression, Decision tree, etc. and conclude which model is the best to use. Finally predict the price of tomorrow and next week’s.

**Dataset**
1.  Extracted the data for Bitcoin, Ape, ADA, Ethereum, BNB from https://finance.yahoo.com/
2.  Got the one-year data on daily basis and weekly basis as well.
3.  Data has got 10 columns as Date, open, high, low, close, adj close, volume,  previous open/ previous open weekly, previous high/previous high weekly and previous low/previous low weekly.
4.  I have used data for each cryptocurrencies mentioned above in a particular csv file as attached.

**Approach**

1   Data Cleaning - Basically in this data, I only got 2-3 null values, that i rectified using the forward fill. Since it is not feasible to predict the values at a particular date.

2.  Data Visualization - Exploratory data analysis was done, the most important plot was to check for linear relation between the target and feature, I have used the matplotlib module to plot it.

3.  Model training - I used the Linear regression model to train my data, since it was providing the best result.

4.  Model Testing - determined the actual and predicted values to check, how close my prediction is to the actual value.

5.  Evaluation of the model - used R-squared score to evaluate the model, because this is a supervied learning.

6.  Predicting tomorrow’s and next week’s price - predicted the close value using today's open, high and low value.


**Result**
Finally, predicted the price of the crypto for tomorrow and next week as well.


**Tools used**

Pandas

Google Colab Notebook

Matplotlib

Sckit-Learn
