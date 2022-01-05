# Capstone Project

This repository is part of a university semester project in social data science, and the subject is stock price prediction. <br />
Different techniques are used for this. First basic models such as technical analysis and ARIMA-forecasting are developed as baseline prediction-models. The focus in this project is on multivariate LSTM, which is used for both single-step prediction and multi-step prediction. It is multivariate since it includes multiple variables and not just the previous stock price. In this project news sentiment is used as a predictor-variables, meaning this repository also includes a web scraping and sentiment-analysis section. <br />
All prediction models are backtested, making it possible to compare them. <br />
The following is a logical order of what this repository contains:<br />
* ‘Web Scraping’, which includes the code for the web scraping and CSV-files of all three of the data sources
* ‘Stock Data’, which includes the code for import of the stock price data and some EDA
* ‘technical analysis and time series analysis’, which includes basic stock price prediction models and backtesting, using technical analysis and ARIMA.
* ‘Sentiment Analysis’, which includes the natural language processing part, in which the sentiment analysis is performed. This is the processing of the news into different sentiments.
* ‘LSTM multi’ is the last part where the stock data and the sentiment analysis is combined. In this section the LSTM model is build, trained, tested and evaluated using back testing - it includes both single-step and multi-step prediction.
