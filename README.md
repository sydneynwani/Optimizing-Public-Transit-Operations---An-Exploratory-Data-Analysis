# 🚌 Optimizing Public Transit Operations — Exploratory Data Analysis

This repository presents an end-to-end Exploratory Data Analysis (EDA) project based on public transportation trip data from MetroMove Transit Solutions.
The project identifies insights and inefficiencies in passenger behavior, fare structures, and transport mode performance to support data-driven operational improvements.

<img width="2560" height="1770" alt="image" src="https://github.com/user-attachments/assets/e05a5498-342f-4719-abfb-c1118f6e989f" />

## 📊 Project Overview

- **Organization**: MetroMove Transit Solutions
- **Domain**: Transportation Analytics
- **Objective**: Analyze public transport trip data to understand patterns in passenger usage, fares, trip durations, and revenue generation.
- **Goal**: Recommend strategies to improve operational efficiency and customer satisfaction through data-driven insights.


## 🎯 Key Objectives
- Identify passenger usage patterns across different transport modes (Bus, Train, Ferry, Tram).
- Evaluate performance metrics — passenger count, trip duration, and revenue.
- Analyze the relationship between fares, trip durations, and passenger counts.
- Recommend strategies to improve operational efficiency and customer satisfaction through data-driven insights.


## 🧩 Dataset Description
- Trip Date:	Date of each trip
- Mode of Transport:	Bus, Train, Ferry, or Tram
- Passenger Count:	Number of passengers per trip
- Fare Amount:	Amount charged per trip
- Trip Duration:	Trip length in minutes
- Departure Station, Arrival Station:	Trip start and end points

- Dataset Size: 1000 records across 42 days
- Total Passengers: 49,039
- Total Revenue: 1,248,668 units


## 🧮 Tools & Libraries Used
- **Language:** Python
- **Libraries:** pandas · numpy · matplotlib · seaborn
- **Tools:** Jupyter Notebook, Powerpoint, Microsoft Excel


## 🔍 Key Insights
**Passenger Behavior:**
- Trams attracted the highest average passengers per trip; trains had the least.
- Price sensitivity observed — Slightly higher fares correlate with slightly lower ridership.


**Revenue:**
- Buses generated the highest total revenue due to higher availability,
- while trams generated the highest average revenue per trip.


**Performance Metrics:**
- Average trip durations: Bus (96.3 mins) highest, Ferry (92.1 mins) lowest.
- Fare per minute: Bus and Train highest (~0.50), Ferry cheapest (~0.47).


**Fare–Duration Relationship:**
- Weak correlation between fare and trip duration (e.g., Bus: +0.05, Train: –0.12),
- suggesting a flat-rate or zonal pricing model rather than distance-based.


## 💡 Recommendations:
- **Revise Fare Policy:** Align fare structures with trip duration or distance.
- **Optimize Capacity Allocation:** Increase the number of trams and ferries — both popular and cost-efficient.
- **Promote Ferries:** Fastest and cheapest per minute — strong candidate for marketing campaigns.
- **Data Quality:** Improve data collection accuracy (especially trip date and time of departure)
