# Forecasting Avocado Prices using Multiple Regression Techniques

## Data Overview
This project uses avocado prices dataset downloaded from the Hass Avocado Board website in May of 2018. The dataset provides weekly retail scan data for national retail volume (units) and price. The data includes multiple columns such as 

- Date - The date of the observation
- AveragePrice - the average price of a single avocado
- type - conventional or organic
- year - the year
- Region - the city or region of the observation
- Total Volume - Total number of avocados sold
- 4046 - Total number of avocados with PLU 4046 sold
- 4225 - Total number of avocados with PLU 4225 sold
- 4770 - Total number of avocados with PLU 4770 sold

## Data Source
The data used in this project was obtained from the Hass Avocado Board website and compiled into a single CSV file that can be downloaded from Kaggle :
[https://www.kaggle.com/datasets/neuromusic/avocado-prices](https://www.kaggle.com/datasets/neuromusic/avocado-prices)

## Methodology
The goal of this project is to forecast avocado prices using the following techniques:
- Linear Regression
- Random Forest Regressor
- XGB Regressor
- Prophet
- ARIMA
- SARIMAX

The forecast models were evaluated using metrics like R-squared, MAPE, and MAE.

## Future Work
Future work for this project includes packaging and testing the deployment of the forecast models for optimal performance on AWS.
