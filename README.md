# hw10-Time_Series_Analysis

This homework tries to use some simple models to fit Yen/USD settle data. First, we used ARMA and ARIMA time series models, followed by linear reggression comparing the lagged percent change of return to the current percent change of returns .

## Time Series ARMA and ARIMA
* The ARMA model had lower AIC and BIC values compared to the ARIMA model, and would seem to be a better fit. The ARMA model suggests the Yen price will increase over the next 5 days, with a large pop on day 1.
* The GARCH model predicts increasing volatility for Yen returns, with robust correlations.
* However, there is a large uncertainty in the ARMA and ARIMA coefficients as the coefficients of the fit switch signs on the error bars.

## Linear Regression Model
* The linear regression did a terrible job of modelling the data. With an R^2 value of nearly zero, linear regression has almost no predictive power when trying to predict Yen/USD returns based on lagged returns.