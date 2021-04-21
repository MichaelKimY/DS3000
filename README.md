# DS3000
Stock Predictor Project For DS3000

With Forrest Meng (meng.fo@northeastern.edu)

The team built a stock price prediction system by using historical stock prices and historical performance indicators. The historical stock prices are pulled using the yfinance python library. The historical performance indicators are scraped from macrotrends.net. The stock price predictor works by using historical performance indicators alongside historical stock prices to determine which indicators change the most alongside the price. To validate our method, we used cross validated r-squared values for 100 companies across different sectors. We analyzed whether our predictor is more accurate when it comes to stocks from particular sectors. The predicted user ratings are decent for predicting stock prices when given enough data, however it is not completely reliable. We suggest that the model struggles because it fails to consider certain factors that could effect stock price changes such as speculation, U.S. and global economic performance, and an overall lack of data.
