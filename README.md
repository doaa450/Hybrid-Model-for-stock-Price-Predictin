# Hybrid-Model

The objective of this study is to reach an appropriate model to predict the stock close price of One-Step for Telecom Egypt (ETEL).
First Model:
•	Dependent Variable :
  Stock Close Price 
•	Independent Variables from the previous day :
 ( open , 
 Close  , 
 High ,
Low Prices,
 Volume,and
Change)
•	Statistical Model :
Long Short Term Memory (LSTM) network.
Second Model:
•	Dependent Variable :
 Stock Close Price 
•	Independent Variables ( Technical Indicators) from the previous day :
MACD Indicator
Momentum
Rate of change (ROC)
Relative strength Indicator (RSI)
STOCHASTIC Indicator
Bollinger Bands Indicator
Simple Moving Average for 30 days 
Simple Moving Average for 10 days
Exponential Moving Average for 30 days
Exponential Moving Average for 10 days
Average Price
Median Price
Typical Price
•	Statistical Model :
Applying Lasso Regression to select the significant Indicators.
Long Short Term Memory (LSTM) network for making prediction.
Third Model (Hybrid Model):
•	Dependent Variable :
 Stock Close Price 
•	Independent Variables from the previous day :
 Predicated value from the first model,
Predicated value from the Second model,and
 Actual value for stock close Price
•	Statistical Model :
  Ridge Regression
