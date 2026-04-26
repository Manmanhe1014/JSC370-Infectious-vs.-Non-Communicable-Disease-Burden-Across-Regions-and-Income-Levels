# Infectious vs. Non-Communicable Disease Burden Across Regions and Income Levels

A Global Analysis (2000–2021) | JSC370 Final Project | University of Toronto

## Website

[https://manmanhe1014.github.io/JSC370-Infectious-vs.-Non-Communicable-Disease-Burden-Across-Regions-and-Income-Levels/](https://manmanhe1014.github.io/JSC370-Infectious-vs.-Non-Communicable-Disease-Burden-Across-Regions-and-Income-Levels/)

## Project Description

This project analyzes the relationship between economic development and global disease burden across 178 countries from 2000 to 2021. It combines health data from the WHO Global Health Observatory with economic indicators from the World Bank to investigate how infectious versus non-communicable disease patterns differ across WHO regions and World Bank income groups, and which country-level factors — GDP, health spending, urbanization — best explain that variation.

The analysis includes interactive visualizations (choropleth maps, sunburst charts, animated bubble plots) and predictive modeling using XGBoost for both classification (predicting income group) and regression (predicting life expectancy).

## Data Sources

- **WHO Global Health Observatory API**: [https://ghoapi.azureedge.net/api/](https://ghoapi.azureedge.net/api/) — Life expectancy, TB incidence, malaria deaths, HIV infections, NCD mortality
- **World Bank API**: [https://api.worldbank.org/v2/](https://api.worldbank.org/v2/) — GDP per capita, health expenditure, urbanization, population

## Repository Structure

```
├── data/                        # Cleaned and raw datasets
│   ├── who_wb_cleaned.csv
│   └── who_wb_merged_raw.csv
├── index.qmd                    # Main project page (source)
├── viz.qmd                      # Interactive visualizations (source)
├── ml.qmd                       # XGBoost modeling (source)
├── midterm2.ipynb               # Data wrangling and EDA notebook
├── _quarto.yml                  # Quarto website configuration
├── style.css                    # Custom styling
└── report.pdf                   # Downloadable PDF report
```
