# Crude-oil-price-prediction-Forecasting-
This is a Forecasting case study. The objective of this case study is to forecast a crude oil price of 15 days based on previous 5 years of data. Here I apply SARIMA model because data has Seasonality component. 
# Project Overview:
### Step 1: Data Collection 
1: Collect a Data from Investing.in website. Which is a share market data.
### Step 2: EDA 
1: Perform EDA. Check for datatypes, null values, duplicate values, variable linearity, perform visualization to analyse the data.
2: Check missing missing dates and impute it with median so as to match time frequency.
### Step 3: Making Data stationary 
1: Check for Stationarity. 
2: Data was non Stationary confirmed by applying Dickey-Fuller test.
3: Apply differencing methond to make data stationary.
### Step 4: Detection of TREND, SEASONALITY and RESIDUAL components 
1: Data decomposition to find TREND, SEASONALITY and RESIDUAL components.
### Step 5: Outlier Handling & Deployment
1: Handle outlires by applying capping and flooring method.
### Step 6: Model Building
1: Build A SARIMA model due to presence of seasonality component. 
2: Got 0.3 MAPE value so finalise the model and deploy it using streamlit.








