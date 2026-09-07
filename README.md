# XGBoost vs GARCH(1,1) FTSE 100 Volatility Forecasting 

This notebook contains the code used for the dissertation on evaluating the volatility forecasting capabilities of machine learning models against traditional econometric models. 

The analysis compares the XGBoost model against the GARCH(1,1) model for forecasting the realised volatility of the FTSE 100 index. The analysis additionally incorporates the use of additional features to evaluate the forecasting capabilities of the XGBoost model, using the features of basic returns, lagged volatility, lagged volume, unemployment rate, GDP rate and social media post volume.

The models are evaluated using MAE, RMSE and Diebold-Mariano tests. 
