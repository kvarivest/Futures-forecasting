# Futures-forecasting
Futures prices forecasting
based on interdependencies of prices, categorical classifier, trying to predict 12-weeks average price trend (bearish/bullish), expected accuracy about 60% but threshhold is regulated

assemble_prices.ipynb assemble prices from ‘quandl’ to weekly_av_prices.xlsx file
creating models.ipynb generates a lot of ML models, accuracy of models is registered in ensemble_register.txt
choosing_models.xlsx contains pivot table to help to choose best models
using_models.ipynb make predictions (-1,-2,-3,week just as reminder)
