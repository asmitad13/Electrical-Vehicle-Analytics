# Electric Vehicle (EV) Data Analysis Project

This project involves performing a comprehensive analysis of electric vehicle (EV) data to explore trends, adoption patterns, and infrastructure distribution. 

The primary goal is to develop an interactive Tableau dashboard that delivers insights about the EV market and highlights charging station availability. 

---
## Project Overview

### Objective
The project analyzes electric vehicle adoption, identifying trends in registrations, popular EV models, and charging station placement. It builds a Tableau Dashboard to allow interactive exploration of the data and its patterns.

Tableau Dashboard Link:  https://public.tableau.com/app/profile/asmita.deshpande/viz/ElectricVehicleDataAnalysis_17272128962490/ElectricVehicleDataAnalysis

---

# Features

1. **Interactive Tableau Dashboard**:
   - Filters by year, EV make, and location.
   - Visualizes the geographic distribution of EV registrations.
   - Maps EV charging station locations for accessibility analysis.

2. **Analysis Highlights**:
   - Popular EV models and adoption trends over the years.
   - Regional EV adoption disparities.
   - Strategic insights into charging station placements.

3. **Data Cleaning and Preparation**:
   - Standardized and cleaned data for meaningful insights.
   - Calculated key metrics, including EV adoption rates.

---

# Technologies Used

- **Tableau**: For interactive data visualization.
- **Python**: For data cleaning and feature engineering.
- **Pandas**: For data manipulation and preparation.
- **Matplotlib & Seaborn**: For exploratory data analysis (EDA).
- **Excel/CSV Files**: Raw data storage and transformation.

---

# Dataset Information

### Datasets Used

**EV Population Data**:
   - Includes fields such as `Make`, `Model`, `Registration Year`, and `Location`.
   


### Sample Columns
| Column Name          | Description                          |
|----------------------|--------------------------------------|
| `Make`              | Manufacturer of the EV              |
| `Model`             | Specific model of the EV            |
| `Year`              | Registration year                   |
| `Location`          | Geographic location of registration |


---
# Steps in Data Analysis

1. Data Cleaning
- Missing Values: Handle missing or null entries in key columns like Make, Model, or Location.
- Data Types: Convert date columns to datetime and ensure numeric fields like Year are integers.
- Duplicates: Remove duplicate rows.

2. Feature Engineering
- Add calculated fields:
- Vehicle Age = Current Year - Registration Year
- Adoption Rate = (Registrations in Region / Total Registrations) * 100

3. Exploratory Data Analysis (EDA)
   
# Trends Analysis:
- Visualize EV registrations by year.
- Analyze popular manufacturers and models.

# Regional Insights:
- Identify top regions for EV adoption.
- Examine the availability of charging stations relative to EV density.


# Dashboard

![Electric Vehicle Data Analysis](https://github.com/user-attachments/assets/9b200fae-424c-49ad-ab8f-d9cadf21b237)

Visualization Creation:
- Line Chart: EV registrations over time.
- Bar Chart: Most popular EV models.
- Geographic Map: EV registrations and charging station locations.

Interactivity:
- Add filters for Year, Make, and Region.
- Use tooltips to display additional information on hover.

# Insights and Visualizations
- Rapid EV adoption in urban regions.
- Tesla dominates as the top manufacturer.

# Regional Disparities:
Coastal regions show higher adoption rates compared to inland areas.

# Charging Infrastructure:
Charging stations are concentrated in high-EV-density areas, but rural areas lag behind.
