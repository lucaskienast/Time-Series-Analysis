# Time Series Analysis
Overview of common time series analysis procedures and techniques. Split into:

- Data Preparation
- Evaluation Frameworks for Forecast Models
- Univariate Time Series Forecasting
- Multivariate Time Series Forecasting
- Time Series Forecasting with Exogeneous Variables
- Time Series Forecasting with Smoothing Techniques

## Data Preparation
An initial and most important step in forecasting is characterizing the nature of the time series and investigating potential problems that must be taken care of before applying any forecasting methods for effective results.

- Load and explore data
- Feature Engineering
- Data Visualization
- Resampling
- Transformations
- White Noise and Random Walks
- Decomposition
- Stationarization

## Evaluation Frameworks for Forecast Models
The goal of any time series forecasting model is to make accurate predictions. The popular machine learning evaluation techniques like train-test split and k-fold cross-validation do not work on the time-series data in their current form. Time series data expects an order dependence between observations, whereas, in other machine learning datasets, all observations are treated equally.

- Data Partitioning
- Forecast Accuracy Metrics
- Naive Forecast
- Residual Analysis

## Univariate Time Series Forecasting
These are datasets where only a single variable is observed at each time, such as temperature each hour. The univariate time series is modeled as a linear combination of its lags. That is, the past values of the series are used to forecast the current and future.

- Autoregression
- Moving Average
- Autoregressive Moving Average
- Autoregressive Integrated Moving Average
- Seasonal Autoregressive Intergrated Moving Average

## Multivariate Time Series Forecasting
These are datasets where two or more variables are observed at each time. In multivariate time series, each variable is modeled as a linear combination of past values of itself and the past values of other variables in the system.

- Vector Auto-Regression
- Vector Moving Average
- Vector Auto Regression Moving Average

## Time Series Forecasting with Exogeneous Variables

- SARIMA with Exogenous Variables
- Vector Autoregression Moving-Average with Exogenous Regressors

## Time Series Forecasting with Smoothing Techniques
Moving average smoothing is a simple and effective technique in time series forecasting. The same name but very different from the moving average model which we discussed in the beginning. The earlier version of the moving average (MA) is a model of residual errors, whereas this smoothing technique consists of averaging values across a window of consecutive periods.

- Moving Average Smoothing
- Single Exponential Smoothing
- Double Exponential Smoothing
- Triple Exponential Smoothing

## References

Prabhakaran, S. (2019) Time Series Analysis in Python - A Comprehensive Guide with Examples. Available at: https://www.machinelearningplus.com/time-series/time-series-analysis-python/ (Accessed: 16 August 2021)
Prabhakaran, S. (2019) ARIMA Model - Complete Guide to Time Series Forecasting in Python. Available at: https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/ (Accessed: 17 August 2021)
Tiwari, A. (2020) Build Foundation for Time Series Forecasting. Available at: https://towardsdatascience.com/time-series-forecasting-968192b3781a (Accessed: 18 August 2021)
Tiwari, A. (2020) Build Evaluation Framework for Forecast Models. Available at: https://towardsdatascience.com/build-evaluation-framework-for-forecast-models-fbc1bd775edd (Accessed: 19 August 2021)
Shrivastava, S. (2020) Cross Validation in Time Series. Available at: https://medium.com/@soumyachess1496/cross-validation-in-time-series-566ae4981ce4 (Accessed: 19 August 2021)
