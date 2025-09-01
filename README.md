# Weather Analytics: Real-Time Multi-City Forecast Dashboard

### 1. Weather Forecast Dashboard 
A dynamic, interactive Power BI dashboard that tracks and visualizes live weather data and forecasts for multiple cities, providing actionable insights on current conditions, air quality, and trends.

---

### 2. Short Description / Purpose
The Weather Analytics Dashboard is a Power BI report designed to fetch, process, and display real-time weather information and forecasts for multiple locations using a weather API. This tool aims to assist analysts, businesses, and weather enthusiasts in monitoring dynamic weather conditions effectively.

---

### 3. Tech Stack
The dashboard was built using the following tools and technologies:  
- 📊 **Power BI Desktop** – Main visualization and dashboard-building platform  
- 📂 **Power Query** – Data transformation, JSON parsing, and API integration  
- 🧠 **DAX (Data Analysis Expressions)** – Custom measures and dynamic visual logic  
- ☁️ **Weather API** – Source of real-time weather and forecast data  
- 📁 **File Format** – `.pbix` for project development and `.png` for dashboard snapshots  

---

### 4. Data Source
This project uses [WeatherAPI.com](https://www.weatherapi.com/) as the data provider. The API delivers detailed weather data including temperature, humidity, wind speed, pressure, UV index, precipitation, air quality values (PM10, SO2, CO, O3, NO2), sunrise and sunset times, and several-day forecasts, all in JSON format suitable for Power BI integration.

---

### 5. Features / Highlights

**Business Problem**  
Weather-dependent operations and planning require up-to-date, accurate, and location-specific weather intelligence, not always easily accessible in a consolidated visual form.

**Goal of the Dashboard**  
To provide a one-stop interactive dashboard that dynamically displays live weather data and forecasts for user-selected cities, supporting informed decisions and weather trend analysis.

**Walkthrough of Key Visuals**  
- **City Selector:** Switch dynamically among multiple cities (e.g., Hyderabad, Chennai, Manali).  
- **Current Conditions Card:** Displays temperature, weather type (e.g., mist), humidity, wind speed, pressure, UV index, precipitation, and visibility.  
- **7-Day Forecast:** Line chart showing temperature trends and daily weather summaries.  
- **Air Quality Index:** Circular gauge plus values for PM10, SO2, CO, O3, NO2 with qualitative status (e.g., "Good").  
- **Sunrise and Sunset:** Time display for sunrise and sunset for selected city.  
- **Chance of Rain:** Bar chart visualizing rain probabilities across a week.  

**Business Impact & Insights**  
- Enables businesses in logistics, travel, and event planning to monitor weather changes live.  
- Supports environmental monitoring through air quality insights.  
- Facilitates personal and professional weather awareness and risk mitigation.

---

### 6. Screenshots / Demos

![Weather Dashboard Main Screenshot](https://raw.githubusercontent.com/Npps1997/Weather-Forecast-Dashboard/main/weather.PNG)

---

## About

This repository contains a comprehensive Power BI project file for creating a weather analytics dashboard. The project demonstrates API integration, advanced data modeling, and interactive visualization design to support multi-city weather monitoring.

Feel free to use, modify, and customize the dashboard for personal or professional weather reporting needs. For support or suggestions, please open an issue or contact the repository owner.

---
