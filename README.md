# 🦭 Marine Tourism Impact Simulation  
A comprehensive Python model for analyzing **tourism activity**, **economic effects**, **boat emissions**, and **ecological impact on seal populations** across multiple years of marine sightseeing operations.

---

## 📌 Overview  
This project simulates the system-wide impact of marine tourism using real passenger data, vessel specifications, ecological models, and visitor satisfaction metrics.  
It integrates:

- 🛥️ Boat trip operations  
- 🌧️ Weather-induced variability  
- 🦭 Seal population growth & disturbance effects  
- 💼 Job creation, GVA, and tourism revenue  
- 🌍 Greenhouse gas emissions (CO₂, CH₄, N₂O, CO₂-eq)  
- 🙂 Net Promoter Score (NPS) dynamics  

The goal is to provide data-driven insights into sustainability and long-term trends in marine wildlife tourism.

---

## ✨ Key Features

### 🚤 Tourism & Boat Activity Modeling
- Yearly tourist demand based on passenger data, NPS, and ecological conditions.  
- Weather effects influencing cancellations and modified boat trip counts.  
- Two built-in boat configurations with different power usage and emission profiles.

### 🌿 Ecological Impact Modeling
- Sigmoid-based disturbance model estimating seal behavioral loss.  
- Growth model adjusting population size based on tourism pressure.  
- Encounter probability and ecosystem overlap calculations.

### 🌍 Emission Analysis
- Calculates fuel use → emissions for CO₂, CH₄, N₂O.  
- Converts all emissions into **CO₂-equivalents** using standard global warming potentials.

### 💵 Economic Impact
- Estimates tourism-driven changes to local jobs, revenue, and GVA.  
- Year-over-year economic adjustments based on simulated tourist activity.

### 😀 Visitor Satisfaction (NPS)
- Annual NPS recalculation with penalties determined by:
  - Seal disturbance  
  - Cancellations  
  - Emissions  
  - Encounter probability  



