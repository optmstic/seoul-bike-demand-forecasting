# Decision Support Systems Project - IBM Data Analyst Capstone Project

## 🚲 Demand Forecasting for Seoul's Bicycle-Sharing System

This project was developed as part of the IBM Data Analyst Professional Certificate. It applies real-world data analysis techniques to understand and forecast bicycle rental demand in Seoul, South Korea.

Using R, APIs, and machine learning, this end-to-end solution includes:

- **Data collection** via web scraping and OpenWeather API
- **Data cleaning** and feature engineering with tidyverse
- **Exploratory data analysis** and visual storytelling
- **Predictive modeling** using regularized regression (`glmnet`)
- **Interactive dashboard** deployment using R Shiny

The goal is to simulate a real business scenario where a city planner or transportation company could use the dashboard to monitor and anticipate demand, improving service efficiency.

### Folder Structure
```text
.
├── main.R # Pipeline controller
├── R/ # Scripts for scraping, API, cleaning, EDA, modeling
├── data/raw/ # Raw datasets
├── data/processed/ # Cleaned datasets
├── output/plots/ # Graphical outputs
├── output/models/ # Trained ML models
├── report.pdf # Data analysis report
└── README.md
```

### Results

- Cleaned datasets (CSV)
- Multiple EDA visualizations
- Forecasting model with high R²
- Trained model file (`.rds`)
- Shiny dashboard with filtering and time-based visualizations

> Run `main.R` to execute the full pipeline and launch the app.
