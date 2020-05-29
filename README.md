# covid-2019-forecast-challenge
Proposed solution for Sberbank COVID-2019 Forecast Challenge 2020
https://ods.ai/competitions/sberbank-covid19-forecast

Datasets could be found here:
https://github.com/CSSEGISandData/COVID-19


Repo consists of two files:

1. COVID-2019-Challenge_v.1.0.ipynb 
A baseline model for predicting number of confirmed cases and deaths.
XGBRegressor was trained on dataset with features:
- population density
- median age
- urban population rate
- days from first confirmed case date
- previous day confirmed cases
- previous day confirmed deaths

2. Most active cases to date.ipynb
Simple notebook for plotting dynamic of top 10 countries with most active cases to current date