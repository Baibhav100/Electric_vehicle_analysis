# Electric Vehicle Data Analysis Dashboard

## Project Overview

This project presents an interactive Tableau dashboard built on electric vehicle registration data. The objective is to analyze the EV market from multiple angles, including adoption trends, state-wise distribution, leading manufacturers, popular models, CAFV eligibility, and electric range performance. [web:17]

## Problem Statements

The dashboard was created to answer the following questions:

1. How has electric vehicle adoption changed over time?
2. Which states have the highest number of electric vehicles?
3. Which manufacturers dominate the EV market?
4. Which EV models are most popular?
5. What is the distribution of Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs)?
6. How many vehicles are eligible for Clean Alternative Fuel Vehicle (CAFV) incentives?
7. What does the average electric range tell us about EV technology and efficiency? [web:13][web:17]

## Dataset Used

The analysis uses the `Electric_Vehicles.csv` dataset provided for the project. The dataset includes key EV attributes such as model year, state, manufacturer, model name, electric range, vehicle type, and CAFV eligibility. [file:21][web:17]

## Methodology

The project followed a structured workflow:

### 1. Data Collection
The EV dataset was gathered and used as the foundation for the dashboard analysis. [file:21]

### 2. Data Preparation
The data was reviewed and cleaned before analysis. This step typically includes handling missing values, standardizing labels, and ensuring fields such as year, state, and manufacturer are usable for grouping and aggregation. [web:17]

### 3. Metric Definition
Core metrics were defined to summarize the dataset, including:
- Total vehicles
- Average electric range
- BEV count
- PHEV count
- CAFV eligibility split [web:17]

### 4. Visualization Selection
Different chart types were used to match the analytical need:
- Area chart for vehicle growth over time
- Map for geographic distribution
- Bar chart for top manufacturers
- Treemap for top vehicle models
- Donut chart for CAFV eligibility [web:17]

### 5. Dashboard Development
The selected visuals were combined into a single Tableau dashboard with filters and interactive elements, allowing users to explore the EV market dynamically. [web:13][web:17]

## Key Insights

The dashboard highlights several important insights:
- EV adoption has grown steadily over the years.
- A few states account for a large share of registered EVs.
- Tesla and a small group of manufacturers dominate the market.
- A limited number of models contribute most of the registrations.
- CAFV eligibility shows the role of incentives in supporting adoption. [web:17]

## Problem-to-Solution Mapping

| Problem Statement | Solution Implemented |
|---|---|
| Understand EV growth over time | Built an area chart using model year to show adoption trends. [web:17] |
| Identify leading states | Used a geographic map to visualize total EV count by state. [web:17] |
| Find dominant manufacturers | Created a bar chart ranking manufacturers by vehicle count. [web:17] |
| Discover popular models | Used a treemap to show the top EV models by volume. [web:17] |
| Measure BEV vs PHEV split | Built a donut chart to compare vehicle type distribution. [web:17] |
| Check CAFV eligibility | Displayed eligibility breakdown to understand incentive impact. [web:17] |
| Evaluate EV efficiency | Used average electric range as a KPI to represent technology progress. [web:17] |

## Tools Used

- Tableau Public
- CSV dataset
- Data cleaning and transformation
- Interactive dashboard design [web:17]

## How to Run the Project

1. Download the dataset.
2. Open the Tableau workbook or dashboard.
3. Connect Tableau to the CSV file.
4. Refresh the data source if needed.
5. Explore the dashboard using the available filters and charts. [file:21][web:17]

## Future Scope

Possible enhancements for this project include:
- Adding time-series forecasting for EV adoption.
- Comparing EV adoption across regions on a per-capita basis.
- Including charging station density analysis.
- Adding more advanced filtering by year, model, and manufacturer.
- Creating a second dashboard for policy and infrastructure planning. [web:17]

## Conclusion

This project turns raw electric vehicle data into an interactive analytical dashboard that explains market growth, regional adoption, manufacturer share, model popularity, and incentive eligibility. It is useful for business analysis, policy planning, academic study, and portfolio presentation. [web:17]

## Dashboard Link

[View the Tableau Dashboard](https://public.tableau.com/authoring/ElectricVehicleDataAnalysis_17583850628090/MainDashboard#1)