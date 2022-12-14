# Forecasting the U.S. Unemployment Rate with Time Series and Machine Learning Models 

<br>

This repository contains source codes used for my thesis on the U.S. unemployment rate time series forecasting. 



Forecasting unemployment rate has been a great interest to many researchers and economists,  as it is a good quantitative indicator of the current U.S. economy.  The aim of this study is to use the unemployment rate data provided by the Bureau of Labor Statistics (BLS) to propose time series models that accurately predict the U.S. unemployment rate. Multiple time series models were compared ranging from a simple median model, simple and multi-linear regressions, more complex Autoregressive Integrated Moving Average (ARIMA) models, to machine learning algorithms. The parameters of the ARIMA models were chosen by selecting the lowest AIC value, and the hyperparameters for machine learning models were tuned by performing a grid search using the predefined split. Root Mean Squared Error (RMSE) was an evaluation metric used in this study, and the model with the lowest RMSE was deemed to be a superior model. The root mean square error (RMSE) was used to measure the difference between the predicted and actual values of the series. The best model was a Moving Average with a RMSE of 0.238, which was the lowest score among the models. Our study demonstrated that a simple time series model like a moving average could indeed outperform the cutting-edge machine learning models in making forecasts. 

<br>



## Time Series Models Used:
- a median model
- simple and multi-linear regressions
- a random walk
- a moving average
- an Autoregressive Integrated Moving Average (ARIMA)
- SVM (machine learning)
- XGBoost (machine learning)
- Random Forest (machine learning)
