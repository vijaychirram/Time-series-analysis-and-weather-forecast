# Time Series Analysis and Weather Forecast Project

## Project Description
This project is an experimental Data Science side project using Python to conduct Time Series Analysis and Weather Forecasts.

## Data Source
The data have been downloaded from the website http://rp5.ru/. The data are average daily temperatures collected by the weather station 2978 in Helsinki from January 2015 to September 2019.

## Tasks

This project sets and addresses the following questions: 
* How to conduct a Time-Series Analysis project from raw data?
* How to deal with a Time-Series data that has seasonality?
* Implementing the Moving Average to capture long-term fluctuations
* Parameter Selection for the model using GRID Search
* Make Weather Forecasts using the SARIMAX model
* How to diagnose the model performance using charts and other metrics (AIC score, RMSE value)?

## Article

[Medium post](https://medium.com/@llmkhoa511/time-series-analysis-and-weather-forecast-in-python-e80b664c7f71)

datetime – The timestamp indicating when the measurements were recorded.
T_mu – Likely the mean temperature (T) over a specific period (e.g., hourly, daily).
Po_mu – Possibly the mean atmospheric pressure at sea level (Po).
P_mu – Possibly the mean atmospheric pressure at station level (P).
Ff_mu – Likely the mean wind speed (Ff).
Tn_mu – Likely the mean minimum temperature (Tn) over a specific period.
Tx_mu – Likely the mean maximum temperature (Tx) over a specific period.
VV_mu – Possibly the mean visibility (VV).
Td_mu – Likely the mean dew point temperature (Td).
T_var – Likely the variance of temperature (T).
Po_var – Variance of atmospheric pressure at sea level (Po).
P_var – Variance of atmospheric pressure at station level (P).
Ff_var – Variance of wind speed (Ff).
Tn_var – Variance of minimum temperature (Tn).
Tx_var – Variance of maximum temperature (Tx).
VV_var – Variance of visibility (VV).
Td_var – Variance of dew point temperature (Td).
