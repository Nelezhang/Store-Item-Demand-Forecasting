# Store-Item-Demand-Forecasting
In this project, the data of store-item sales from Kaggle.com has been used to predict monthly sales in the upcoming 6 months. This project utilizes one of the 50 different items at one of the 10 different stores. 
Naïve and seasonal naïve models, autoregressive integrated moving average models (ARIMA), regression-based models, advanced exponential smoothing models were developed for the prediction. The smoothing method of trailing moving average for residuals was created to smooth out the noise in this time series and provide better results. Another additional variation constructed is the autoregressive model for residuals, which is utilized to enhance the regression and advanced exponential smoothing models. The evaluation of the performance of the forecasting models was based on the accuracy measures of RMSE and MAPE. As a conclusion according to the comparison, the two-level model with quadratic trend and seasonality with a trailing moving average for residuals was considered as the best model to be applied for the entire dataset forecasting.
Dataset:
test.csv
train.csv
