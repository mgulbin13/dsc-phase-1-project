# Flying Smarter: Data-Driven Decisions for Safer Aviation Ventures
by Matthew Gulbin and Calvin Lee

---

This project focuses on Exploratory Data Analysis (EDA) and visualization using a cleaned aviation dataset. This repository aims to uncover patterns and insights related to aircraft safety by analyzing key fields such as **Weather Conditions**, **Engine Count/Type**, and whether an aircraft is **Amateur Built**.  

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Dataset](#dataset)  
3. [Analysis Sections](#analysis-sections)  
    - Weather Conditions  
    - Engine Count/Type  
    - Amateur Built 
4. [Visualizations](#visualizations)
5. [Findings](#findings)  
6. [Links](#links)

---

## Project Overview

The primary objective of this project is to analyze aviation incidents and assess their correlation with specific factors:
- The safety of different aircraft manufacturers under varying weather conditions.
- The relationship between engine configurations and incident outcomes.
- Comparing the safety of amateur-built aircraft against professionally manufactured ones.

Visualizations are provided to support the findings, making the insights easier to interpret.

---

## Dataset

The dataset, `AviationData_clean.csv`, contains cleaned aviation incident records. The analysis focuses on incidents from the year 2002 onwards to maintain relevance for modern aircraft.  

**Key Fields Analyzed:** 
- `Make` (Aircraft Manufacturer)  
- `Total.Fatal.Injuries`, `Total.Serious.Injuries`, `Total.Minor.Injuries`
- `Weather.Condition`
- `Number.of.Engines`, `Engine.Type` 
- `Amateur.Built`  

---

## Analysis Sections

### 1. Weather Conditions
**Objective:** Analyze the impact of weather conditions on the safety of the top 5 most common aircraft manufacturers in the dataset.  

**Key Steps:**
  - Filter data for incidents from 2002 onward.
  - Focus on two weather conditions: **Visual Meteorological Conditions (VMC)** and **Instrument Meteorological Conditions (IMC)**.
  - Analyze incident counts and fatalities for each manufacturer under different weather conditions.
  - Visualize average fatalities using bar charts.

**Key Findings:**
- **Boeing** is the safest manufacturer in inclement weather (IMC).
- **Bell** has the highest average fatalities under poor weather conditions.

---

### 2. Engine Count/Type
**Objective:** Analyze the relationship between engine count/type and aviation safety.

**Key Steps:**
  - Analyzed number of incidents by engine count
  - Filtered by engine type
  - Focused on the three engine types with the least number of accidents
  - Looked at the average number of fatalities for the three engine types.


**Key Findings:**
  - Aircraft with two engines have the lowest number of accidents.
  - Turbo Jet and Turbo Shaft engines are associated with better safety and performance metrics.
  - **Airbus** and **Boeing** demonstrate lower accident rates for two-engine aircraft.

---

### 3. Amateur Built
**Objective:** Compare the safety records of amateur-built versus professionally manufactured aircraft.  

**Key Steps:**
  - Divide the dataset into amateur and professional categories.
  - Identify the top 5 manufacturers in each category.
  - Analyze and compare average fatalities, serious injuries, and minor injuries.

**Key Findings:**
- **Rotorway** is the safest among amateur-built aircraft.
- **Boeing** is the safest among professionally manufactured aircraft.

---

## Visualizations

### Summary
<img
src="img/Screenshot 2025-01-23 at 6.05.48 PM.png"
alt="Summary" />

### Weather Analysis
<img
src="img/Screenshot 2025-01-23 at 6.10.26 PM.png"
alt="Summary" />

### Engine Count/Type
<img
src="img/Screenshot 2025-01-23 at 6.10.43 PM.png"
alt="Summary" />

<img
src="img/Screenshot 2025-01-23 at 6.11.02 PM.png"
alt="Summary" />

<img
src="img/Screenshot 2025-01-23 at 6.11.20 PM.png"
alt="Summary" />

<img
src="img/Screenshot 2025-01-23 at 6.11.36 PM.png"
alt="Summary" />

### Amateur vs. Professional

<img
src="img/Screenshot 2025-01-23 at 6.11.59 PM.png"
alt="Summary" />

<img
src="img/Screenshot 2025-01-23 at 6.12.09 PM.png"
alt="Summary" />

<img
src="img/Screenshot 2025-01-23 at 6.12.21 PM.png"
alt="Summary" />

---

## Conclusion

1. **Weather Analysis:**  
   - Manufacturers differ significantly in safety across weather conditions. **Boeing** emerges as a safe choice for inclement weather conditions.  

2. **Engine Count/Type:**
    - Aircraft equipped with two engines experience the fewest accidents.
    - Turbo Jet and Turbo Shaft engines are linked to superior safety metrics.
    - **Airbus** and **Boeing** two-engine models show lower accident rates.
   
2. **Amateur vs. Professional:**  
   - Professional aircraft generally have more fatalities than amateur-built aircraft, potentially due to their higher usage rate.  
   - **Rotorway** and **Boeing** stand out as the safest in their respective categories.  

---

## Links

- [Tableau Dashboard](https://public.tableau.com/views/FlatironPhase1project/ProjectDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)