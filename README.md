# Time-Series-with-ARIMA
Time Series forecasting using Seasonal ARIMA. Applied statistical tests like Augmented Dickey–Fuller test to check stationary of series. Checked ACF ,PACF plots. Transformed series to make it stationary

##Time Series with ARIMA models.

Includes yfinance, exploratory analysis, stationarity test,ARIMA model hyper parameter tuning and residual analysis.

The aim of this repository is study the behaviour of a particular stock, in this case - SAIL (A Public Sector Unit of the Indian Govt listed on NSE). In no way, this is an investment advice. This is just for study purposes. 

Throughout the notebook, following libraries have been used

1. [Pandas](https://pandas.pydata.org/).
2. [Numpy](https://numpy.org/).
3. [Scikit-leaarn](https://scikit-learn.org/stable/).
4. [Matplotlib](https://matplotlib.org/).
5. [Seaborn](https://seaborn.pydata.org/).
6. [Statmodels](https://www.statsmodels.org/stable/index.html).

While pursuing my master's in Data Science and Analytics, I came across Time Series models in ARIMA and how it could be applied to various problems. I decided to use it on a particular stock and observe its behaviour patterns One things I would like to improve on this is to go one level above and apply forecasting techniques. 

Data is scraped using the yahoo finance api (https://pypi.org/project/yfinance/)

