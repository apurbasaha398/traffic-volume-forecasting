# Predicting Daily Traffic Volume at Arizona I-10 / Loop 202 Interchange

## Project Overview
The aim of this project is to predict the daily traffic volume at the Arizona I-10 / Loop 202 interchange. The focus is given on pre-COVID-19 data, specifically the daily traffic data for the years 2018 and 2019. Due to the impact of COVID-19 on traffic patterns, this historical data provides a stable basis for our time-series analysis. The dataset includes data for both eastbound and westbound traffic.

## Data Source
For this project, TMAS dataset was used, which can be found at [Federal Highway Administration (FHWA) website](https://www.fhwa.dot.gov/policyinformation/tables/tmasdata/).

## Project Description
For this project, traffic data for the years 2018 and 2019 was retrieved from the FHWA TMAS dataset. To enhance the analysis, additional features were created to capture time-series information, including day of the week, day of the month, month, long weekends, holidays, lags, and more. Traditional statistical time-series models like Linear regression, ETS (Error, Trend, Seasonality) and SARIMA (Seasonal Autoregressive Integrated Moving Average), ARIMAX, Decomposition were used to fit the data. A comparison between these models were made to identify which approach offers better predictive accuracy in terms of MAPE and RMSSE score. Finally, meaningful insights were derived from the time-series analysis that can help identify key factors influencing traffic volume.
