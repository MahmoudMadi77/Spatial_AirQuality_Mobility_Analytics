# Traffic & Air Pollution Analysis in Chicago

This project provides an in-depth analysis of **taxi mobility patterns** and **air quality (PM2.5 levels)** in Chicago. Leveraging advanced geospatial analytics, temporal data aggregation, and clustering algorithms, the analysis reveals critical insights into urban mobility and its environmental impact.

---

## Project Overview

- **Objective**: Explore the relationship between taxi pickup patterns and urban air pollution by merging and analyzing two datasets.
- **Location**: Chicago, USA
- **Data Sources**: 
  - Taxi pickup records (with timestamps and geolocations)
  - PM2.5 air quality measurements from monitoring stations

---

## Key Techniques Used

- **Exploratory Data Analysis (EDA)**
- **Spatio-temporal aggregation** using GeoHash and hourly time bins
- **Correlation analysis** using Pearson correlation coefficients
- **Clustering with DBSCAN** to detect spatial pollution or pickup hotspots
- **Silhouette score** evaluation for clustering effectiveness
- **Parameter tuning** for optimal DBSCAN results

---

## Highlights & Findings

- **Hourly Taxi Patterns**: Clear demand cycles found with peak activity during rush hours.
- **Air Quality Trends**: PM2.5 levels exhibit noticeable daily and weekly variations, including high-pollution spikes.
- **Mobility-Pollution Correlation**: Moderate correlation observed between taxi activity and PM2.5 concentration.
- **DBSCAN Clustering**: Successfully identified urban hotspots of both taxi activity and pollution using optimized parameters.

---

## Team Members

- **Mahmoud Madi**
- **Abdullah Soubhi Abdulkarim**
- **Moaaz Saed Alshehadat**
- **Omar Hassan Al Hamadi**
- **Humaid Mohamed Al Ali**

---

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/MahmoudMadi77/Spatial_AirQuality_Mobility_Analytics
cd Spatial_AirQuality_Mobility_Analytics
```
## 2. Install Dependencies
Make sure the following Python packages are installed:

- numpy  
- pandas  
- matplotlib  
- seaborn  
- scikit-learn  
- python-geohash  
- jupyter  

You can install them all with:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn python-geohash jupyter
```

## 3. Run the Notebook

Launch the Jupyter Notebook:

```bash
jupyter notebook "True Final FDS Project"
```