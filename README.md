# ETS Forecasting Project (R)

Time series forecasting using ETS models with the fpp3 framework.

## Files
- Forecasting_Project.Rmd
- IA_data.csv

## What it does
- Cleans & converts data to tsibble
- Visualises trend & seasonality
- Fits ETS models (manual + auto)
- Residual diagnostics (Ljung–Box)
- Forecasts last 24 months + next 24 months

## Requirements
```r
install.packages(c("fpp3","readr"))
