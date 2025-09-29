# SCT_DS_04
traffic accident analysis

# 🚦 Traffic Accident Data Analysis  

This project focuses on analyzing **traffic accident data** to identify patterns related to **road conditions, weather, and time of day**. The analysis also highlights **accident hotspots** and key **contributing factors** leading to severe accidents.  


---

## 📌 Objective  

The main goals of this project are:  
- To explore accident data and uncover hidden patterns.  
- To study the impact of **road condition, weather, and time of day** on accidents.  
- To identify **accident hotspots** using geospatial visualizations.  
- To analyze **contributing factors** such as alcohol involvement, driver demographics, and traffic control.  

---

## 🗂️ Dataset  

The dataset contains detailed information about traffic accidents, including:  

- `State Name` – State/UT where the accident occurred  
- `City Name` – City of accident  
- `Year`, `Month`, `Day of Week` – Date and time-related features  
- `Time of Day` – Morning, Afternoon, Evening, Night  
- `Accident Severity` – Severity level of accident  
- `Number of Vehicles Involved`  
- `Vehicle Type Involved`  
- `Number of Casualties`  
- `Number of Fatalities`  
- `Weather Conditions` – Sunny, Rainy, Foggy, etc.  
- `Road Type` – Highway, Urban road, Rural road  
- `Road Condition` – Dry, Wet, Icy, etc.  
- `Lighting Conditions` – Daylight, Dark (street lights present/absent)  
- `Traffic Control Presence` – Signals, signs, etc.  
- `Speed Limit (km/h)`  
- `Driver Age`, `Driver Gender`  
- `Driver License Status`  
- `Alcohol Involvement` – Yes/No  
- `Accident Location Details`  

---

## ⚙️ Project Workflow  

1. **Data Exploration & Cleaning**  
   - Handled missing values and ensured data consistency.  
   - Standardized categorical variables.  

2. **Exploratory Data Analysis (EDA)**  
   - Accident distribution by **state, city, and year**  
   - Patterns by **time of day, weather, and road conditions**  
   - Severity analysis by **driver demographics**  

3. **Visualization**  
   - Bar plots, histograms, and heatmaps for trend analysis  
   - Accident hotspots visualized with **geospatial maps** (using Folium/HeatMap)  
   - Correlation between **accident severity** and contributing factors  

4. **Insights Extracted**  
   - Identified high-risk **time slots** and **weather conditions**  
   - Highlighted road types and conditions with maximum casualties  
   - Revealed impact of alcohol, driver age, and speed limits on accident severity  

---

## 📈 Results & Key Findings  

- **Weather & Road Conditions:** Accidents are more frequent on **wet roads during rainy conditions**.  
- **Time of Day:** Higher accident severity observed during **night hours** due to poor lighting.  
- **Hotspots:** Certain highways and urban intersections are more accident-prone.  
- **Contributing Factors:**  
  - Alcohol involvement increases fatal accidents significantly.  
  - Young drivers (18–25) contribute to a higher number of accidents.  
  - Absence of traffic control increases accident frequency.  

---

## 🚀 How to Run  

1. Clone the repository  
   ```bash
   git clone https://github.com/yourusername/traffic-accident-analysis.git
   cd traffic-accident-analysis
