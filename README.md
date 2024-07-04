# Time-Series-Forecasting-Lake-Ontario-Water-Level

This repository contains the analysis and forecasting of the monthly mean water levels of Lake Ontario. The project involves exploratory data analysis, model building, and forecasting using various time series models.

# Project Overview

The variations in Lake Ontario's water level significantly impact lake management, environmental planning, and community safety. The objective of this project is to use historical water level data along with neighboring lakes' water level data, mean temperature, mean net precipitation, and mean net evaporation data to forecast future water levels.

# Data Description

The dataset includes:

1. Monthly Mean Water Level of the Great Lakes (in meters)
2. Mean Temperature of Toronto (°C)
3. Monthly Net Evaporation (in mm)
4. Monthly Net Precipitation (in mm)

Time Period: January 1980 - December 2017

# Data sources:

Great Lakes Water Level Data: https://www.lre.usace.army.mil/Missions/Great-Lakes-Information/Great-Lakes-Information-2/Water-Level-Data/ 
NOAA Technical Reports: https://www.glerl.noaa.gov/pubs/tech_reports/glerl-083/UpdatedFiles/

# Models Used
1. Time Series Linear Regression
2. Exponential Smoothing (ETS)
3. Seasonal ARIMA (SARIMA)
4. Regression with Arima Errors
5. VAR
6. Dynamic Harmonic Regression 
7. Neural Network Autoregression (NNAR)
8. TBATS
   
# Results and Findings

Best Models: The ARIMA and TBATS models provided the best forecast when compared to other models with respect to actual test data.
Metrics: The RMSE and MAE values for ARIMA and TBATS models were low, indicating good predictions on the forecast.

# Conclusion

ARIMA and TBATS models are effective for forecasting the monthly mean water levels of Lake Ontario. The ARIMA model, considering model complexity, would be more robust.

# Future Scope

1. Water Consumption: Incorporate water consumption and human intervention-related data.
2. Inflow/Outflow Monitoring: Monitor inflow rates into Lake Ontario for better insights into water levels.
3. Advanced Models: Explore advanced modeling techniques like LSTM and ensemble methods.
4. Wind Impact: Consider the impact of wind on temporary changes in water levels.

# Discussion and Contact

For discussions, questions, or further information about the project, feel free to contact me at pandanihar1996@gmail.com.

