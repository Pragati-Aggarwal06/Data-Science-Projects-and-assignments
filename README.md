# ⚡ Electricity Consumption Across Cities Dataset

## 📌 Project Overview

The **Electricity Consumption Across Cities** dataset contains monthly electricity usage statistics for multiple Indian cities. It includes demographic information, weather conditions, energy consumption across different sectors, electricity tariffs, peak demand, renewable energy contribution, and electrification rates.

This dataset is suitable for **Power BI**, **Excel**, **Python**, **SQL**, and **Data Analytics** projects. It enables users to analyze electricity demand patterns, compare cities and regions, evaluate seasonal variations, and build interactive dashboards.

---

# 📂 Dataset Information

* **Dataset Name:** Electricity Consumption Across Cities
* **File Format:** Excel (.xlsx)
* **Granularity:** Monthly city-level records
* **Country:** India
* **Time Period:** Monthly data (Year and Month)
* **Primary Key:** `Record_ID`

---

# 📊 Dataset Columns

| Column Name                    | Description                                          |
| ------------------------------ | ---------------------------------------------------- |
| Record_ID                      | Unique identifier for each record                    |
| City                           | Name of the city                                     |
| State                          | State where the city is located                      |
| Region                         | Geographic region (North, South, East, West, etc.)   |
| City_Tier                      | Classification of city (Tier-1, Tier-2, etc.)        |
| Year_Month                     | Combined Year and Month                              |
| Year                           | Year of observation                                  |
| Month                          | Month name                                           |
| Season                         | Season corresponding to the month                    |
| Population                     | Estimated population of the city                     |
| Number_of_Households           | Total households in the city                         |
| Avg_Temperature_C              | Average monthly temperature (°C)                     |
| Residential_Consumption_MU     | Residential electricity consumption (Million Units)  |
| Commercial_Consumption_MU      | Commercial electricity consumption (Million Units)   |
| Industrial_Consumption_MU      | Industrial electricity consumption (Million Units)   |
| Agricultural_Consumption_MU    | Agricultural electricity consumption (Million Units) |
| Total_Consumption_MU           | Total electricity consumption (Million Units)        |
| Per_Capita_Consumption_kWh     | Electricity consumption per person (kWh)             |
| Tariff_Rate_INR_per_unit       | Electricity tariff per unit (INR)                    |
| Peak_Demand_MW                 | Maximum electricity demand (MW)                      |
| Power_Outage_Hours             | Average power outage duration (hours)                |
| Renewable_Energy_Share_Percent | Renewable energy contribution (%)                    |
| Electrification_Rate_Percent   | Percentage of electrified households                 |

---

# 🎯 Project Objectives

* Analyze electricity consumption trends across Indian cities.
* Compare electricity usage among residential, commercial, industrial, and agricultural sectors.
* Study seasonal and yearly consumption patterns.
* Evaluate the impact of temperature on electricity demand.
* Analyze renewable energy contribution across regions.
* Monitor peak demand and power outages.
* Compare electricity tariffs among cities.
* Build interactive dashboards for decision-making.

---

# 📈 Suggested Power BI Dashboard

### Dashboard 1 – Consumption Overview

* KPI Cards

  * Total Electricity Consumption
  * Average Per Capita Consumption
  * Average Tariff Rate
  * Peak Demand
* Filled Map

  * Total Consumption by State
* Clustered Column Chart

  * Consumption by City
* Donut Chart

  * Consumption by Sector
* Line Chart

  * Monthly Consumption Trend

---

### Dashboard 2 – Regional Analysis

* Bar Chart

  * Region-wise Electricity Consumption
* Tree Map

  * Consumption by State
* Matrix

  * Region × Sector
* Slicer

  * Year
  * Region
  * City Tier

---

### Dashboard 3 – Renewable Energy & Reliability

* Gauge Chart

  * Renewable Energy Share
* Scatter Plot

  * Temperature vs Electricity Consumption
* Line Chart

  * Peak Demand Trend
* Column Chart

  * Power Outage Hours by City

---

# 📊 Recommended DAX Measures

* Total Consumption
* Average Residential Consumption
* Average Commercial Consumption
* Average Industrial Consumption
* Average Agricultural Consumption
* Average Tariff
* Average Temperature
* Total Peak Demand
* Renewable Energy %
* Average Outage Hours
* Per Capita Consumption
* Year-over-Year Growth
* Month-over-Month Growth

---

# 📌 Business Questions

1. Which city consumes the most electricity?
2. Which state has the highest electricity demand?
3. Which sector contributes the most to electricity consumption?
4. How does electricity usage vary by season?
5. Does higher temperature increase electricity consumption?
6. Which cities experience the highest peak demand?
7. Which cities face the most power outages?
8. Which region has the highest renewable energy share?
9. Which city has the highest per capita electricity consumption?
10. How do tariff rates vary across cities and states?

---

# 🛠 Tools Used

* Microsoft Power BI
* Microsoft Excel
* SQL (Optional)
* Python (Optional)
* DAX
* Power Query

---

# 📚 Possible Use Cases

* Electricity Demand Forecasting
* Energy Consumption Analysis
* Renewable Energy Monitoring
* Smart City Analytics
* Government Energy Planning
* Utility Company Reporting
* Academic Data Analytics Projects

---

# 📌 Conclusion

This dataset provides a comprehensive view of electricity consumption across Indian cities by combining demographic, environmental, and energy-related indicators. It is ideal for building professional Power BI dashboards, practicing DAX calculations, performing exploratory data analysis (EDA), and generating actionable insights into energy usage, demand patterns, and sustainability.
