# Earthquake Magnitude Forecasting using ARMA

This project uses ARMA (AutoRegressive Moving Average) modeling to forecast earthquake magnitudes in South Asia based on historical seismic data.

## Objective
To model and forecast seismic activity trends over time using time series techniques.

## Dataset
- **Source**: Kaggle
- **Feature Used**: Average monthly earthquake magnitudes

## Methodology
1. **Data Preprocessing**
   - Converted timestamps to datetime and aggregated by month
   - Ensured regular time intervals for ARMA modeling

2. **Stationarity & Transformation**
   - Applied ADF test to assess stationarity
   - Used differencing where necessary

3. **Modeling**
   - Performed ACF/PACF analysis
   - Built and tuned ARMA(p,q) models using `statsmodels`

4. **Evaluation**
   - Validated model fit via residual analysis
   - Forecasted earthquake magnitude trends for the next 12 months

## Tools Used
- Python, Pandas, Statsmodels
- Matplotlib, Seaborn

## Author
Aahna Shresth  
[GitHub Profile](https://github.com/aahna-shresth)
