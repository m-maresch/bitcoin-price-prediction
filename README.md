# Bitcoin Price Prediction
This repository contains a notebook showing how to predict the prices of a single Bitcoin for 1 hour in the future using Deep Learning.

Cells 2-4 of the notebook talk to the Alpha Vantage API to get current Bitcoin data. Here you can access and explore the most recent data (you have to provide your own API Key here), e.g. I tried out Linear Regression to see what the resulting function would look like. Cells 5-13 use historical bitcoin data to construct a model that makes prediction for 1 hour in the future. The model achieves an validation loss of 0.0089. Practically speaking the model misses the actual value by 0-50€.  

If you have any questions about the notebook or you'd like to know how to run it then feel free to contact me via [mmaresch.com](http://mmaresch.com). You'll need an Alpha Vantage API Key and the *Bitcoin Historical Data* Dataset on Kaggle (see below for links) to run the notebook yourself.

# Dependencies
Thanks to everyone contributing to any of the following projects:
- TensorFlow
- NumPy
- Matplotlib
- Pandas
- Scikit-learn
- Requests

Thanks to Alpha Vantage for their awesome [API](https://www.alphavantage.co/).

Thanks to Zielak for the [*Bitcoin Historical Data*](https://www.kaggle.com/mczielinski/bitcoin-historical-data) Dataset on Kaggle.

Thanks to the authors of the tutorial [*Time series forecasting*](https://www.tensorflow.org/tutorials/structured_data/time_series) at [tensorflow.org](https://www.tensorflow.org), which shows how to do many kinds of time series forecasting using TensorFlow. 
