# Time Series Analysis
Overview of common time series analysis procedures and techniques. Split into:

- Data Preparation
- Evaluation Frameworks for Forecast Models
- Univariate Time Series Forecasting
- Multivariate Time Series Forecasting
- Time Series Forecasting with Exogeneous Variables
- Time Series Forecasting with Smoothing Techniques

## Installation
Use `git clone` to get a copy of this repository.
```
$ git clone https://github.com/lucaskienast/Time-Series-Analysis.git
$ cd Time-Series-Analysis
```
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
An exogenous variable is one whose value is determined outside the model and is imposed on the model. In other words, variables that affect a model without being affected by it.

- SARIMA with Exogenous Variables
- Vector Autoregression Moving-Average with Exogenous Regressors

## Time Series Forecasting with Exponential Smoothing
Moving average smoothing is a simple and effective technique in time series forecasting. The same name but very different from the moving average model which we discussed in the beginning. The earlier version of the moving average (MA) is a model of residual errors, whereas this smoothing technique consists of averaging values across a window of consecutive periods. Exponential smoothing uses an exponentially decreasing weight for past observations.

- Single Exponential Smoothing
- Double Exponential Smoothing
- Triple Exponential Smoothing

## References

Arzamendia, O. (2019) Time Series Forecasting - A Getting Started Guide. Available at: https://towardsdatascience.com/time-series-forecasting-a-getting-started-guide-c435f9fa2216 (Accessed: 21 August 2021)

Brownlee, J. (2020) How to Create an ARIMA Model for Time Series Forecasting in Python. Available at: https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/ (Accessed: 22 August 2021)

Brownlee, J. (2019) How to Model Volatility with ARCH and GARCH for Time Series Forecasting in Python. Available at: https://machinelearningmastery.com/develop-arch-and-garch-models-for-time-series-forecasting-in-python/ (Accessed: 22 August 2021)

Brownlee, J. (2017) How to Remove Trends and Seasonality with a Difference Transform in Python. Available at: https://machinelearningmastery.com/remove-trends-seasonality-difference-transform-python/ (Accessed: 18 August 2021)

Cordeiro, M. (2020) A Step-by-step Implementation of a Trading Strategy in Python using ARIMA + GARCH models. Available at: https://medium.com/analytics-vidhya/a-step-by-step-implementation-of-a-trading-strategy-in-python-using-arima-garch-models-b622e5b3aa39 (Accessed: 22 August 2021)

Dierckx, T. (2020) ARIMA-GARCH forecasting with Python. Available at: https://medium.com/@thdierckx?p=7a3f797de3ff (Accessed: 22 August 2021)

Etienne, B. (2019) Time Series in Python - Exponential Smoothing and ARIMA process. Available at: https://towardsdatascience.com/time-series-in-python-exponential-smoothing-and-arima-processes-2c67f2a52788 (Accessed: 21 August 2021)

Kumar, R. (2020) Time Series Model(s) - ARCH and GARCH. Available at: https://medium.com/@ranjithkumar.rocking/time-series-model-s-arch-and-garch-2781a982b448 (Accessed: 21 August 2021)

Nazarava, A. (2019) Prediction task with Multivariate Time Series and VAR model. Available at: https://towardsdatascience.com/prediction-task-with-multivariate-timeseries-and-var-model-47003f629f9 (Accessed: 21 August 2021)

Paul, J. (2019) A Blueprint for Time Series Forecasting. Available at: https://towardsdatascience.com/a-blueprint-for-time-series-9f865609bfa2 (Accessed: 21 August 2021)

Prabhakaran, S. (2019) Time Series Analysis in Python - A Comprehensive Guide with Examples. Available at: https://www.machinelearningplus.com/time-series/time-series-analysis-python/ (Accessed: 16 August 2021)

Prabhakaran, S. (2019) ARIMA Model - Complete Guide to Time Series Forecasting in Python. Available at: https://www.machinelearningplus.com/time-series/arima-model-time-series-forecasting-python/ (Accessed: 17 August 2021)

Quantopian (2016) Integration, Cointegration, and Stationarity. Available at: https://www.youtube.com/watch?v=Pn_RiDbK82M (Accessed: 16 August 2021)

Singh, A. (2018) A Gentle Introduction to Handling a Non-Stationary Time Series in Python. Available at: https://www.analyticsvidhya.com/blog/2018/09/non-stationary-time-series-python/ (Accessed: 22 August 2021)

Shrivastava, S. (2020) Cross Validation in Time Series. Available at: https://medium.com/@soumyachess1496/cross-validation-in-time-series-566ae4981ce4 (Accessed: 19 August 2021)

Tiwari, A. (2020) Build Foundation for Time Series Forecasting. Available at: https://towardsdatascience.com/time-series-forecasting-968192b3781a (Accessed: 18 August 2021)

Tiwari, A. (2020) Build Evaluation Framework for Forecast Models. Available at: https://towardsdatascience.com/build-evaluation-framework-for-forecast-models-fbc1bd775edd (Accessed: 19 August 2021)

Twiari, A. (2020) Let's Forecast Your Time Series using Classical Approaches. Available at: https://towardsdatascience.com/lets-forecast-your-time-series-using-classical-approaches-f84eb982212c (Accessed: 20 August 2021)
