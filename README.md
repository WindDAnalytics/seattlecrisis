# 📊 Seattle Crisis Dashboard

A data visualization and analysis dashboard built in Kaggle to explore public safety incidents reported to Seattle police. This project leverages real-world data to uncover trends, analyze call types, and display incident locations across the city.

---

## 📁 Dataset Overview

- **Source**: Seattle Open Data Portal
- **Records**: ~99,000+ incidents
- **Date Range**: May 15, 2015 – April 12, 2025
- **Columns**: 25 attributes including:
  - `Reported Date`, `Call Type`, `Disposition`, `Precinct`, `Sector`, `Beat`
  - Officer demographics and classification of incidents

---

## 🔧 Tools & Libraries Used

- `Pandas` – data manipulation
- `Matplotlib` – static chart visualization
- `Plotly` – interactive charting (converted to matplotlib for compatibility)
- `Folium` – interactive mapping of recent incident locations
- `NumPy` – numerical operations

---

## 📌 Key Visualizations

### 🔹 Incident Trends Over Time
- Line and bar plots of daily and weekly incidents
- Stacked visualizations by Precinct and Sector

### 🔹 Call Type & Precinct Analysis
- Top 5 call types by count and precinct
- Bar charts colored by trend (increase or decrease)

### 🔹 Sector Heat Trends
- Calculated recent 3-day average vs. 30-day average
- Colored bar plot to show rising or falling sectors

### 🗺️ Interactive Map
- The latest 100 incidents mapped using Folium
- Dispositions shown as popups

---

## 🌍 Geolocation Mapping

Each police beat was manually mapped with latitude and longitude values for accurate visualization. These coordinates were cleaned and merged into the dataset to support spatial plots.

---

## 📈 Sample Analysis Outputs

- **Incidents Per Day**: `Line graph` of counts over time
- **Precinct Breakdown**: `Stacked bar` for the last 30 days
- **Disposition Types**: Horizontal bar chart
- **Sector Trends**: 3-day vs. 30-day trend comparison
- **Call Type Frequency**: Top 5 visualized in grouped bars

---

## 🚀 How to Use

This dashboard is hosted and runs on Kaggle. To replicate or explore:
1. [Download the dataset](https://cos-data.seattle.gov/)
2. Open in a Kaggle notebook or local Jupyter environment
3. Run through the cells sequentially to view insights

---

## 🧠 Future Improvements

- Add interactive filters by time, sector, and disposition
- Incorporate severity or urgency scoring
- Enable time-lapse animations using Plotly or Kepler.gl
- Deploy on Streamlit or Flask for public use

---

## 📍 Contact

**Created by**: Damarcus Thomas  
**Kaggle Notebook**: [_[Link to your Kaggle notebook]_](https://www.kaggle.com/code/dtthomas/seattle-crisis-data-set-dashboard)
**Email**: 146stat@gmail.com

---

> This project demonstrates how public datasets can be used to surface critical insights around mental health, policing, and resource allocation across urban environments.

