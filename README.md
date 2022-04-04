# bitpredict
## Intro
Repo for testing various forecasting models on crypto currency trading data. Specifically, we focus on bitcoin data (arbitararily chosen, the techniques and functions can easily be applied on the others as well in most cases). 

We compare the performance of two approaches (a deep learning approach using LSTMs and multi-layer perceptrons vs a classical approach using ARIMA) on the same data. 

## Dataset
The data set was originally obtained from [kaggle](https://www.kaggle.com/philmohun/cryptocurrency-financial-data) and copied over into the the datasets directory for ease of reference. 

## notebooks
The notebooks directory contains two collab notebooks that detail our experiments with the various forecasting models. 

The first notebook ([BitPredict-LSTM.ipynb](https://github.com/arjunshenoymec/bitpredict/blob/main/notebooks/BitPredict-LSTM.ipynb)] also explains some transformations, adjustments to be done on the data before passing it to sections that deal with analysis and training. 

## References
https://www.kaggle.com/philmohun/cryptocurrency-financial-data

https://otexts.com/fpp3/intro.html

https://github.com/mrdbourke/tensorflow-deep-learning/blob/main/10_time_series_forecasting_in_tensorflow.ipynb

https://www.machinelearningplus.com/time-series/time-series-analysis-python/

https://machinelearningmastery.com/decompose-time-series-data-trend-seasonality/ 

https://towardsdatascience.com/the-easiest-way-to-adjust-your-data-for-inflation-in-python-365490c03969

https://towardsdatascience.com/lets-forecast-your-time-series-using-classical-approaches-f84eb982212c

https://machinelearningmastery.com/time-series-forecasting-supervised-learning/

https://machinelearningmastery.com/how-to-develop-lstm-models-for-time-series-forecasting/

https://towardsdatascience.com/lstm-time-series-forecasting-predicting-stock-prices-using-an-lstm-model-6223e9644a2f

https://towardsdatascience.com/time-series-forecasting-predicting-stock-prices-using-an-arima-model-2e3b3080bd70 

https://medium.com/deep-learning-with-keras/lstm-understanding-the-number-of-parameters-c4e087575756

machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/

https://towardsdatascience.com/lets-forecast-your-time-series-using-classical-approaches-f84eb982212c

https://tensorflow.rstudio.com/guide/tensorflow/tensors/#shape

https://otexts.com/fpp2/stationarity.html#stationarity

https://tinyurl.com/yjk4f372

https://www.machinelearningplus.com/time-series/augmented-dickey-fuller-test/

https://otexts.com/fpp2/stationarity.html#differencing
