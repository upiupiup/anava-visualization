# Solar Energy Data Visualization & Forecasting for Smart Grid Optimization

[![Python Version](https://img.shields.io/badge/Python-3.12.4-3776AB.svg?style=flat&logo=python)](https://www.python.org/)
[![Frameworks](https://img.shields.io/badge/Frameworks-Pandas%2C%20NumPy%2C%20Matplotlib%2C%20Seaborn-purple.svg)](#)
[![Visualization](https://img.shields.io/badge/Visualization-Infographic%20%26%20Analysis-blue.svg)](#)

This project presents a data-driven visualization and analysis of Indonesia’s solar energy landscape. It integrates raw solar potential data, energy production records, and national energy statistics to explore utilization gaps, production variability, and system-level implications for smart grid optimization.

The project was developed as part of **ANAVA #20**, a national data analytics and visualization competition organized by Universitas Gadjah Mada, where the project was selected as a **Top 12 out of 96 teams**.

## Project Overview

This repository contains the complete analytical workflow for visualizing and analyzing solar energy data, starting from raw geospatial and time-series datasets through exploratory analysis, forecasting, and insight-driven storytelling.

The project focuses on:
- Visualizing solar energy potential and its geographical distribution
- Analyzing variability in solar energy production
- Examining Indonesia’s energy mix and fossil dependency
- Applying time-series forecasting to support energy planning
- Translating technical analysis into clear, interpretable visual insights
- Proposing a data-driven smart grid concept integrating IoT, forecasting, and explainable decision support

## Data Sources

The analysis integrates multiple datasets, including:
- Solar potential and irradiance data (Global Horizontal Irradiance / GHI)
- National solar capacity and energy mix statistics
- Geospatial boundary data for regional analysis
- Solar plant generation and weather sensor time-series data

All datasets were cleaned, transformed, and aligned to support consistent analysis and visualization.

## Methodology

The analytical workflow includes:
1. Data research and sourcing from primary and institutional references  
2. Data cleaning, transformation, and aggregation  
3. Exploratory Data Analysis (EDA) on spatial and temporal patterns  
4. Time-series forecasting experiments using:
   - ETS  
   - ARIMA  
   - SARIMA  
   - Prophet  
5. Model comparison and selection based on data characteristics  
6. Insight synthesis and visual storytelling aligned with technical findings  

SARIMA was selected as the final forecasting approach due to its suitability for seasonal solar production patterns.

## Project Structure
```
.
├── fonts/
├── src/
│ ├── vis 1/
│ │ ├── irena_kapasitas_plts.xlsx
│ │ ├── ne_50m_admin_0_countries.cpg
│ │ ├── ne_50m_admin_0_countries.dbf
│ │ ├── ne_50m_admin_0_countries.prj
│ │ ├── ne_50m_admin_0_countries.README.html
│ │ ├── ne_50m_admin_0_countries.shp
│ │ ├── ne_50m_admin_0_countries.shx
│ │ └── ne_50m_admin_0_countries.VERSION.txt
│ │
│ ├── vis 3/
│ │ └── GHI.tif
│ │
│ ├── vis 4/
│ │ ├── Plant_1_Generation_Data.csv
│ │ ├── Plant_1_Weather_Sensor_Data.csv
│ │ ├── Plant_2_Generation_Data.csv
│ │ └── Plant_2_Weather_Sensor_Data.csv
│
├── notebook.ipynb
└── README.md
```

## Notebook Description

The `notebook.ipynb` contains:
- Data loading and preprocessing
- Exploratory analysis of solar potential, variability, and energy mix
- Time-series forecasting experiments
- Analytical interpretation of model behavior
- Visualizations supporting insight development and storytelling

## Visualization Output

The final visualization and infographic output can be accessed here:

**Visualization Result:**  
https://drive.google.com/file/d/1Tx_2sIe0rFJS1Xl7aERStChdwJ9u-yWh/view?usp=sharing


## Key Outcomes

- Clear visualization of the gap between high solar potential and low utilization
- Evidence-based explanation of solar intermittency and fossil dependency
- Forecast-driven reasoning to support coordinated grid management
- A coherent narrative connecting technical analysis and system-level innovation

## Tools & Technologies

- Programming: Python 3.12.4  
- Data Analysis: Pandas, NumPy  
- Visualization: Matplotlib, Seaborn  
- Forecasting: ETS, ARIMA, SARIMA, Prophet  
- Domain: Energy Analytics, Smart Grid Systems  

## Contrubutors

- Aufii Fathin Nabila
- Batsnah Nabila Zahidah
