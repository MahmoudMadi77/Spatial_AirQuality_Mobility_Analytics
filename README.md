
# 🚖📊 Traffic & Air Pollution Analysis in Chicago

This project provides an in-depth analysis of taxi mobility patterns and air quality (specifically PM2.5 levels) in Chicago. Leveraging advanced geospatial analytics, temporal data aggregation, and clustering algorithms, the analysis reveals critical insights into urban mobility and environmental impacts.

---

## 📋 Project Overview

- **Objective**: Understand the relationship between taxi pickup patterns and urban air pollution from two different data sources and join them for a comprehensive analysis.
- **Location**: Chicago
- **Data**: Taxi pickup records and air quality measurements (PM2.5)

---

## 🛠️ Key Techniques Used

- **Exploratory Data Analysis (EDA)**
- **Spatio-temporal aggregation** using GeoHash and hourly bins
- **Correlation analysis** (Pearson coefficient)
- **DBSCAN clustering** and silhouette score evaluation
- **Parameter tuning** for optimal clustering

---

## 📈 Highlights & Findings

- **Hourly Taxi Patterns**: Identified clear hourly peaks indicating predictable demand cycles.
- **Air Quality Trends**: Observed distinct temporal fluctuations and occasional high-pollution events.
- **Moderate Correlation**: Found a noticeable, though moderate, correlation between taxi pickup frequency and PM2.5 pollution levels.
- **Effective Clustering**: Successfully identified significant urban hotspots through optimized DBSCAN clustering.

---

## 🚀 Getting Started

### Prerequisites
Ensure you have:
- Python 3.x installed
- Dependencies listed below

---

## 💻 Usage

Run the notebook to reproduce the analysis:
```bash
jupyter notebook Traffic_Pollution_Analysis.ipynb
```

---

## 📦 Dependencies
- numpy
- pandas
- matplotlib
- seaborn
- sklearn
- geohash
- jupyter

---

## 📌 Future Work
- Integrate additional datasets (traffic data, weather conditions)
- Investigate deeper causal relationships
- Explore advanced spatial regression techniques

---


