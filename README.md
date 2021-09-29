# Stock-market-prediction-using-Numerical-and-Textual-analysis
This project is a part of The Sparks Foundation GRIP internship which highlights **Time Series analysis** of historical stock prices and **Sentiment Analysis** of news headlines.
The historical stock prices dataset has been extracted from https://finance.yahoo.com/ and the news headlines data is used from https://bit.ly/36fFPI6.

### Approach:
 - I used **ARIMA** (AutoRegressive Integrated Moving Average) model to make stock market prices predictions using the historical stock prices data of last 15 years. 
 - Extracted Sentiment Scores from given newspaper headlines data, with the help of NLTK's **SentimentIntensityAnalyzer**.
 - Used different Machine Learning algorithms to make the predictions - Random Forest Regressor, Decision Tree Regressor, AdaBoost, XGBoost.
 - Random Forest Regressor performed best on the hybrid data with an **RMSE: 0.172**
 
### References: 
https://medium.com/swlh/temperature-forecasting-with-arima-model-in-python-427b2d3bcb53
https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/
