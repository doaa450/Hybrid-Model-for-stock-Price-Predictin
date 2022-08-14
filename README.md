# Hybrid-Model
------------------------------------------------------------------------------------------------------------------------------------------
```
The objective of this study is to reach an appropriate model to predict the stock close price of One-Step for Telecom Egypt (ETEL).
```
## First Model:

### Dependent Variable :
   Stock Close Price 
###	Independent Variables from the previous day :
 ( open , 
 Close  , 
 High ,
Low Prices,
 Volume,and
Change)
###	Statistical Model :
Long Short Term Memory (LSTM) network.
## Second Model:
###	Dependent Variable :
 Stock Close Price 
### Independent Variables ( Technical Indicators) from the previous day :__
 MACD Indicator__
 Momentum__
 Rate of change (ROC)__
 Relative strength Indicator (RSI)__
 STOCHASTIC Indicator__
 Bollinger Bands Indicator__
 Simple Moving Average for 30 days__ 
 Simple Moving Average for 10 days__
 Exponential Moving Average for 30 days__
 Exponential Moving Average for 10 days__
 Average Price__
 Median Price__
 Typical Price__
###	Statistical Model :
Applying Lasso Regression to select the significant Indicators.
Long Short Term Memory (LSTM) network for making prediction.
## Third Model (Hybrid Model):
###	Dependent Variable :
 Stock Close Price 
###	Independent Variables from the previous day :
 Predicated value from the first model,
Predicated value from the Second model,and
 Actual value for stock close Price
###	Statistical Model :
  Ridge Regression
