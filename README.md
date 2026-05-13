# Seoul Bike Demand Forecasting

Academic project for **Decision Support Systems** and the **IBM Data Analyst Capstone**.

This project builds an end-to-end analytical workflow for understanding and forecasting bicycle-sharing demand in Seoul, South Korea. It combines data collection, cleaning, exploratory analysis, predictive modelling, and an interactive Shiny dashboard.

---

## Objective

Simulate a decision-support tool for a city planner or bicycle-sharing operator who needs to:

- Monitor bicycle rental demand
- Understand demand patterns across time and weather conditions
- Forecast expected rentals
- Support operational planning and resource allocation

---

## Workflow

1. **Data collection**  
   Web scraping and OpenWeather API calls.

2. **Data preparation**  
   Cleaning, feature engineering, and creation of processed datasets.

3. **Exploratory data analysis**  
   Visual analysis of demand patterns, seasonality, and weather relationships.

4. **Predictive modelling**  
   Demand forecasting using regularized regression with `glmnet`.

5. **Decision-support dashboard**  
   Interactive R Shiny dashboard for exploring trends and forecasts.

---

## Main outputs

- Cleaned analytical datasets
- Exploratory visualisations
- Forecasting model
- Interactive Shiny dashboard
- Academic report documenting the full workflow

---

## Technologies

`R` · `tidyverse` · `glmnet` · `Shiny` · `Web Scraping` · `OpenWeather API` · `Forecasting` · `Decision Support Systems`

---

## How to run

Open the project in RStudio or another R environment and run:

```r
source("main.R")
```

This executes the pipeline and launches the dashboard, assuming the required packages and API configuration are available.

---

## Notes

This is an academic decision-support project. The forecast model is intended for analytical demonstration and should be validated further before production use.
