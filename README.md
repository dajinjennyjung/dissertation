# Dissertation: Senegal’s Great Green Wall: Monitoring and Simulations via Vegetation Index

This repository contains the code and data used in the project “Senegal's Great Green Wall: Monitoring and Simulations via Vegetation Index”. The project evaluates vegetation change in Senegal’s Sahel region—before and after the Great Green Wall Initiative (GGWI)—using satellite-derived vegetation indices and time-series forecasting models.

## Overview
The study measures vegetation dynamics using NDVI and EVI from MODIS, climate variables from ERA5-Land, and soil characteristics from OpenLandMap. It assesses long-term trends, climate-vegetation relationships, and forecasts future vegetation using two modelling approaches:

* SARIMA (Seasonal ARIMA)
* LSTM (Long Short-Term Memory neural networks)

The analysis focuses on four protected areas central to Senegal’s GGWI implementation:
Six Forage (SF), Barkedji Dodji (BD), Ferlo-Nord (FN), and Ferlo-Sud (FS).

## Key Research Questions
* How has vegetation cover in Senegal’s GGWI zone changed over time?
* What climate factors correlate most strongly with vegetation health?
* What do time-series models predict about future vegetation in the region?

## Main Findings
- Vegetation generally improved post-2008 across all sites, with Ferlo-Sud showing the highest NDVI values.
- Soil moisture and thermal radiation were the strongest positive correlates of vegetation; evaporation-related variables were strongly negative.
- LSTM models outperformed SARIMA in most regions for RMSE and MAE, indicating stronger predictive accuracy.
- FS was the only site where SARIMA performed slightly better, likely due to strong seasonality and data stability.
