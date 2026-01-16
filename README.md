# Berlin-Airbnb-Market-Analysis
An end-to-end data analysis project investigating Berlin's rental market trends as of late 2025. This project utilizes SQL for data engineering and Python for exploratory data analysis (EDA) to identify high-yield investment districts and pricing anomalies.
# 📊 Berlin Rental Market Deep-Dive (Sept 2025)

## 🎯 Project Overview
In the wake of shifting energy costs and housing regulations in Germany, this project analyzes the Berlin Airbnb and rental landscape using data finalized on **September 23, 2025**. 

The goal is to provide a "Market Health Report" for a hypothetical real estate investment firm looking to enter the Berlin market in 2026.

## 🛠️ Tech Stack & Skills
- **Storage:** Kaggle Public Dataset (Berlin Listings)
- **Data Cleaning:** Python (Pandas) for handling missing 'Kaltmiete' vs 'Warmmiete' values.
- **Analysis:** SQL (Window Functions for neighborhood ranking).
- **Communication:** Business-ready README and visualizations.

## 📈 Key Research Questions
1. **The Cost of Living:** Which districts show the highest "Utility Gap" (difference between base rent and total cost)?
2. **Post-Summer Supply:** How did availability change in tourist hubs (Mitte/Kreuzberg) after the Summer 2025 season?
3. **Price Outliers:** Identifying listings that are priced 2 standard deviations above the district median.

## 📁 Repository Structure
- `/data`: Contains the raw listings.csv (Source: Kaggle/Inside Airbnb).
- `/notebooks`: Jupyter Notebooks with EDA and visualizations.
- `/scripts`: SQL queries used for neighborhood aggregation.

## 🚀 Impact
This analysis identifies three "Emerging Districts" where ROI is projected to be 12% higher than the city average due to current supply-demand imbalances found in the Q3 2025 data.
