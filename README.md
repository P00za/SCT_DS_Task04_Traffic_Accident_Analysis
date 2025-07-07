# 🚗 SCT_DS_Task04 - Advanced Traffic Accident Analysis

This project is part of my Data Science Internship under **Skillcraft Technologies**. In this task, I explored and analyzed a real-world dataset of U.S. traffic accidents from March 2023 to identify patterns, hotspots, and contributing factors using advanced data science techniques.

## 📊 Objective

To analyze the US_Accidents_March23 dataset and uncover patterns related to:
-  Road and traffic conditions
-  Weather impact on accident severity
-  Time-of-day and accident frequency
-  Geographic accident hotspots
-  Feature importance using machine learning

##  Dataset

- File: `US_Accidents_March23.csv`
- Size: ~6.5 million records, 47 columns

##  Tools & Libraries

- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Random Forest, KMeans)
- Folium for interactive map visualization

##  Key Features & Steps

1. **Data Cleaning & Preprocessing**
   - Handled missing values, filtered outliers (e.g., unrealistic temperatures)
   - Created new time-based features (hour, day, month, time of day)

2. **Visual Exploratory Data Analysis**
   - Correlation heatmaps
   - Boxplots for severity vs. weather/time
   - Histograms for accident frequency by hour/day

3. **Geo-Clustering**
   - Used `KMeans` to group accident hotspots based on coordinates
   - Visualized them using `folium` interactive maps

4. **Machine Learning: Feature Importance**
   - Trained a Random Forest Classifier
   - Identified key predictors of severity: Visibility, Wind Speed, and Temperature

##  Key Findings

| Factor              | Insight                                                                 |
|---------------------|-------------------------------------------------------------------------|
| Time of Day         | More severe accidents at Night and Evening                              |
| Weather Conditions  | Fog, Thunderstorms, and Snow lead to higher severity                    |
| Visibility          | Lower visibility strongly correlates with increased accident severity   |
| Location Clusters   | Hotspots detected near highways and major urban zones                   |

##  Future Improvements

- Add city/state-specific analysis using GIS libraries
- Integrate external APIs (Google Maps, OpenWeather)
- Build a dashboard using Power BI or Streamlit for live data interaction
- Build a predictive model to classify accident severity



