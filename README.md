# ⚡ Electric Vehicle Data Analysis Dashboard

## 📌 Project Overview

This project presents an interactive **Tableau Dashboard** built using Electric Vehicle (EV) registration data. The dashboard provides insights into EV adoption, manufacturer dominance, popular vehicle models, state-wise distribution, and the market share of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs).

The primary objective of this project is to transform raw EV registration data into meaningful business insights through interactive visualizations.

---

# 📷 Dashboard Preview

<p align="center">
  <img src="Screenshot 2026-06-26 165557.png" alt="Electric Vehicle Dashboard" width="1000"/>
</p>

---

# 🎯 Business Problem

The dashboard answers the following business questions:

- How many electric vehicles are currently registered?
- What is the distribution of BEVs and PHEVs?
- Which vehicle manufacturers dominate the EV market?
- Which EV models are the most popular?
- Which states have the highest EV registrations?
- What insights can businesses and policymakers derive from EV adoption patterns?

---

# 📂 Dataset

The project uses the **Electric_Vehicles.csv** dataset containing EV registration details such as:

- VIN (Vehicle Identification Number)
- State
- County
- City
- Make
- Model
- Model Year
- Electric Vehicle Type
- Electric Range
- CAFV Eligibility
- Electric Utility
- Legislative District

---

# ⚙️ Project Workflow

## 1. Data Collection

Imported the Electric Vehicle registration dataset into Tableau.

---

## 2. Data Cleaning

Performed preprocessing tasks including:

- Handling missing values
- Standardizing categorical values
- Validating state and manufacturer names
- Removing inconsistencies

---

## 3. KPI Creation

The following KPIs were created:

- Total Vehicles
- Total Battery Electric Vehicles (BEV)
- Total Plug-in Hybrid Electric Vehicles (PHEV)
- Percentage share of BEVs
- Percentage share of PHEVs

---

## 4. Dashboard Development

The dashboard includes the following visualizations:

- KPI Cards
- Top 10 Vehicle Models
- Top 10 Vehicle Manufacturers
- State-wise EV Distribution Map

Interactive filters allow users to explore the dataset dynamically.

---

# 📊 Dashboard Features

### 🚗 KPI Cards

Displays:

- Total Vehicles
- Total BEVs
- Total PHEVs
- BEV Percentage
- PHEV Percentage

---

### 🏭 Top 10 Manufacturers

Ranks manufacturers based on total registered electric vehicles.

Key insight:
- Tesla dominates the market by a significant margin.

---

### 🚘 Top 10 Vehicle Models

Shows the most popular electric vehicle models.

Key insight:
- Tesla Model Y and Tesla Model 3 account for a major share of EV registrations.

---

### 🗺️ State-wise Distribution

Interactive geographical map showing EV registrations across different states.

Key insight:
- Washington has the highest concentration of registered EVs in the dataset.

---

# 💡 Key Insights

- Battery Electric Vehicles (BEVs) account for approximately **76.92%** of total registrations.
- Plug-in Hybrid Electric Vehicles (PHEVs) contribute around **23.08%**.
- Tesla is the leading EV manufacturer.
- Tesla Model Y and Model 3 are the most registered EV models.
- EV adoption is concentrated in a few states, particularly Washington.

---

# 🛠️ Technologies Used

- Tableau Public
- Microsoft Excel / CSV Dataset
- Data Cleaning
- Data Visualization
- Dashboard Design

---

# 🚀 How to Use

1. Clone this repository.
2. Open the Tableau Workbook.
3. Connect the `Electric_Vehicles.csv` dataset.
4. Refresh the data source if required.
5. Explore the dashboard using the interactive visualizations.

---

# 📈 Future Enhancements

Potential improvements include:

- Time-series analysis of EV adoption
- EV growth forecasting
- Charging station analysis
- Manufacturer market share trends
- Regional comparison dashboard
- Additional filters (Year, State, Make, Model)

---

# 📌 Conclusion

This Tableau dashboard provides a comprehensive overview of electric vehicle registrations across the United States. It enables users to analyze market trends, compare manufacturers, identify popular vehicle models, and understand the geographic distribution of EV adoption through an interactive and business-friendly interface.

---

# 🔗 Tableau Dashboard

👉 **View the Interactive Dashboard**

https://public.tableau.com/views/ElectricVehicleDataAnalysis_17583850628090/MainDashboard?:showVizHome=no

---
