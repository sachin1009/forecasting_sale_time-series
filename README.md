Champagne Sales Forecasting with ARIMA & SARIMA
This project demonstrates time series forecasting on monthly champagne sales data using ARIMA and SARIMA models. It involves checking for stationarity, differencing, analyzing autocorrelation, and building predictive models to forecast future sales.

📁 Dataset
File: perrin-freres-monthly-champagne-.csv

Columns:

Month — Monthly time index

Sales — Champagne sales figures

🔧 Steps Performed
1. Load and Preprocess the Data
Load CSV using pandas

Convert Month to datetime and set as index

Plot original sales data

2. Check Stationarity
Applied ADF (Augmented Dickey-Fuller) test to check if the data is stationary.

Performed first differencing and seasonal differencing to make the data stationary.

3. Autocorrelation Analysis
Used ACF and PACF plots to identify patterns and help select ARIMA parameters (p, d, q).

4. Build Models
ARIMA Model — Handles trend and noise.

SARIMA Model — Adds seasonality handling.

5. Make Forecasts
Predicted values on existing data to validate model.

Generated future dates and forecasted sales ahead using the SARIMA model.

📦 Libraries Used
python
Copy
Edit
pandas
numpy
matplotlib
statsmodels
📊 Output
Line plots of original vs predicted sales

ACF/PACF graphs for model tuning

Future sales forecasts visualized

