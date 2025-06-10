# 🚗 UK Road Accident Dashboard

## 📊 Project Overview

This Power BI dashboard analyzes UK road accident data (2021–2022), exploring how accident severity, road conditions, and locations interrelate. We use advanced visuals and filters to uncover actionable insights on road safety.

---

## 🧩 Problem Statement

To understand factors influencing accident frequency and severity across the UK, this dashboard investigates:
- Total casualties and average speed limits
- Police forces with highest incident counts
- Districts with over 1,000 accidents
- Vehicle types most commonly involved
- Correlation between vehicles involved and casualties
- Trends in accidents by year, quarter, month, and day
- Junction types most prone to accidents
- Districts most affected
- Impact of road surface on accident severity

---

## 📁 Dataset Description

- **Accident_Index**: Unique accident ID  
- **Accident_Date**: Date of occurrence  
- **Day_of_Week**: Weekday  
- **Junction_Detail**, **Crime_Junction**, **Junction_Type**: Junction info  
- **Accident_Severity**: Fatal, Serious, Slight  
- **Latitude**, **Longitude**: Location data  
- **District**, **Police_Force**: Administrative areas  
- **Number_of_Casualties**, **Number_of_Vehicles**: Counts  
- **Road_Surface_Conditions**, **Road_Type**, **Speed_limit**, **Light_Conditions**, **Weather_Conditions**: Environmental factors  
- **Time**, **Urban_or_Rural_Area**, **Vehicle_Type**: Additional attributes

---

## 🛠️ Steps Followed

- ✅ **Data Import & Cleaning**: Loaded and scrubbed Excel/CSV data  
- 🔍 **Data Cleaning**: Handled nulls, parsed dates, standardized names  
- 📊 **KPI Cards**: Total casualties and avg speed limit via Card visuals  
- 🧩 **Visuals & Filters**:
  - **Pie Chart**: Accidents by Police Force  
  - **Column Chart** + **Advanced Filter**: Districts with >1,000 accidents  
  - **Column Chart**: Accident counts by vehicle type  
  - **Scatter Plot**: Vehicles involved vs. average casualties  
  - **Line Chart** with Drill-through: Daily, monthly, quarterly, yearly trends  
  - **Sorted Bar Chart**: Junction types linked to accidents  
  - **Top N Filter**: Top districts by accidents  
  - **Clustered Column Chart**: Road surface vs. severity  
- 🔧 **Slicers**: Accident Severity and District for global filtering

---

## 📸 Dashboard Preview

![Dashboard Screenshot](https://github.com/YourUsername/YourRepo/blob/main/UK_Road_Accident_Dashboard.png)

---

## 💡 Key Insights

- 🚦 **T-junctions** are hotspots for accidents  
- 🚗 **Cars** are the most involved vehicle type  
- 🏙️ **Westminster, Lambeth, Barnet** report >1,000 accidents each  
- 📊 A clear rise in **casualties** as the **number of vehicles involved increases**  
- 🌞 **Dry roads** show higher accident frequencies  
- 🚓 **Metropolitan Police** covers ~98% of reported incidents

---

## ✅ Recommendations

1. **Improve T-junction safety**: Install signs, enforce speed limits  
2. **Road safety programs**: Target high-risk districts with community campaigns  
3. **Emergency services**: Deploy ambulances strategically in accident-prone areas  
4. **Vehicle safety**: Mandate airbags and standard safety features in cars  
5. **Road maintenance**: Prioritize dry roads with surface treatments  
6. **Speed enforcement**: Issue fines for overspeeding, especially near junctions

---

## 📁 Files Included

- `UK_Road_Accident_Dashboard.pbix` – Power BI report  
- `UK_Road_Accident_Dashboard.png` – Dashboard snapshot  
- `UK_Road_Accident_Dataset.xlsx` – Original dataset

---

## 🙋‍♂️ About Me

I’m **[Your Name]**, a data analyst specializing in **Power BI, SQL & Python**, with a passion for turning data into impactful stories.  
Check out more here: [GitHub Profile](https://github.com/Sathwik-pabba)

---

## 🔗 Connect with Me

- 💼 [LinkedIn](https://linkedin.com/in/YourProfile)  
- 📫 Email: your.email@example.com
