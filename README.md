Project Name : Can ML predict Stock price movement?
Project Type : Analysis

Problem and Analysis 
There are many technical indicators on historical stock data to predict future prices but none of them are accurate all the time.  Some of them are accurate some of the time.  Stock price movement is so complex it’s hard for most people to analyze, let alone perform a prediction. So let’s see how ML can help.

Solution
In this project, I try to let Machine Learning model study the historical data and let it can come up with its own algorithm to predict future stock prices.    So let’s see how Machine Learning can perform in this area. 
With ML’s result, I can perhaps compare the prediction with one of an existing indicator known as the MACD (Moving Average Convergence Divergence) to see how well the ML model perform against a model created by humans.  MACD allow us to spot a buy or sell signal.

Data :
I plan to use stock data from Yahoo Finance which is publicly available.  Data provided will be at least some of the followings :
a.	Market open, closed prices for the day for X number of days
b.	Market volume for the day for X number of days
c.	Calculated Moving averages to be used as features for ML training
d.	Any other suitable data as I discovered along the project.

Assumptions :
The prediction should use the provided data and create 
a.	A “buy” signal indicating that future prices (after Y number of days) will rise higher
b.	A “sell” signal indicating that future prices (after Y number of days) will drop lower
c.	To validate if a signal is true positive or otherwise, I shall compare it with the price in the next Y trading days and also calculate the % difference from the signal day.

Validation approach :
We will provide daily historical data for one stock eg Google (GOOG) and divide it into training data and validation data.  Once the training model is created, we can test it against the same GOOGLE data but for a different historical period or we can use on new stock data from another stock symbol eg AMAZON (AMZN) for validation on the performance of the ML model.
 
Disclaimer:  This is just for educational purposes. Do not bet your money using this!
