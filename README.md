# DS3000
Stock Predictor Project For DS3000

With Forrest Meng (meng.fo@northeastern.edu)

Project Description

The team built a stock price prediction regression model by using historical stock prices and historical performance indicators. The historical stock prices are pulled using the yfinance python library. The historical performance indicators are scraped from macrotrends.net. The stock price predictor works by running the historical performance indicators alongside historical stock prices into a multiple linear regression model to determine which indicators change the most with the price. The model produces an equation that takes into account six different company performance metrics to determine a stock price.

To validate our method, we used cross validated r-squared values for 100 companies across different sectors. We analyzed the accuracy of our model across sectors, and considered how the amount of data available affect it accuracy. The predicted user ratings are decent for predicting stock prices when given enough data, however it is not always reliable. We suggest that the model struggles because it fails to consider certain factors that could effect stock price changes such as speculation, U.S. and global economic performance, or an overall lack of data.
