# An ensemble of time series models for forecasting with R
Reads in a time series and fits in it the following models:
1) seasonal regression,
2) trend + seasonal regression,
3) Holt-Winters multiplicative,
4) Holt-Winters additive,
5) ARIMA,
6) ARIMA with box-cox transformation,
7) ETS,
8) TBATS.

The program then determines the best-performing model for each forecasting step based on a test split and forecasts "truly out-of-sample" using the best-performer.
