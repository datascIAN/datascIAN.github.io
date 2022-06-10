---
layout: post
title: "Apple Stock Time Series Analysis with ARIMA"
subtitle: "Machine Learning - Regression"
background: '/img/posts/apple-stock-time-series/apple-store.jpg'
---

## Description
This project aims to produce a model that can forecast the price of Apple Inc. stocks. The S&P500 will be used as an exogenous variable to strengthen model performance. This model can be used on any stock. It can be helpful in our investing strategy as it can provide an indication of what to expect in the future. This helps investors plan ahead to maximize gains and minimize losses. 

## Objectives
Train a model than can predict the price of the Apple Inc's stock using ARIMA. 

## Tools
Python was used for this project. The following libraries were utilized:  
- Numpy
- Pandas
- Matplotlib
- seaborn
- scipy
- statsmodels
- Pmdarima

## Steps
1. Loading packages
2. Importing the data from Yahoo!Finance
3. Preprocessing the data
4. Plotting the data
5. Test for Stationarity: ADF test
6. Seasonal decomposition
7. Differencing
8. Log transformation
10. KPSS test
11. ACF and PACF
12. Training the Auto ARIMA model
13. Make Predictions
14. Evaluate Model Performance

## The Data
The stock data for Apple Inc. (APPL) and the S&P500 (^GSPC) were taken directly from Yahoo! Finance using the yfinance library.

```python
raw_data = yfinance.download(tickers= "AAPL, ^GSPC", interval="1d",auto_adjust = True, treads=True, group_by='ticker')
```
<p align="center">
  <img width="100%" height="100%" src="/img/posts/apple-stock-time-series/yahoo-finance-data.jpg" />
</p>

## Data Cleaning and Preprocessing


## EDA


#### Correlation





## Modelling & Evaluation


## Conclusion


---
**The project can be accessed through this [link](https://github.com/datascian/Predicting-the-Price-Range-of-Used-Cars) with the codes and the full [documentation](https://github.com/datascian/Predicting-the-Price-Range-of-Used-Cars/blob/main/John%20Ian%20Castaneda%20-%20CIND%20820%20-%20Final%20Report.pdf).**