# Time_Series_Analysis_with_ARIMAX-NN-LSTM-COPULA

In this project, I integrated COPULA into hybrid ARIMAX-LSTM and hybrid ARIMAX-NN for forcasting greenbond and conventional bond.

The project utlized the lags values as exogenous variables or input variables to forecast the time series data.

The weekly effects was checked by using the lag1, lag2, lag3, lag4 and lag5 as exogenous input variables.

To check the Monthly effect, lag25 was included, then the quaterly effects had the inclusion of lag75.

AIC and BIC values were used to evaluate the performances of the train set of different models.

RMSE, MAPE, MAE were used to evaluate the performances of the test set of the differnt variables

20% of the data was used as the test set or out-of-sample while 80% was used as the train set.

Data preprocessing like stationarity test, differencing were carried out to prepare the data for time series analysis.
