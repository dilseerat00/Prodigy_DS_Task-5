# Traffic Accident Data Analysis

Task5: Analyze traffic accident data to identify patterns related to road conditions, weather, and time of day. Visualize accident hotspots and contributing factors.

## Dataset

- **Source**: [US Accident Dataset from Kaggle](https://www.kaggle.com/code/harshalbhamare/us-accident-eda)
- **File**: `US_Accidents_March23.csv`
- The dataset contains information about traffic accidents in the US, including accident location, weather conditions, road conditions, and timestamps.

## Objective

The main objectives of this analysis are:
- To identify accident hotspots using geospatial data.
- To analyze the impact of road and weather conditions on accident frequency and severity.
- To visualize the distribution of accidents over time (hour of the day, day of the week, month of the year).
  
## Tools and Libraries Used

- **Python**: Core programming language used for analysis.
- **Libraries**:
  - `Pandas` – Data manipulation and analysis
  - `Matplotlib` – Data visualization
  - `Seaborn` – Statistical data visualization
  - `Folium` – Geospatial data visualization (Heatmaps for accident hotspots)
  - `NumPy` – Numerical computing

## Analysis and Visualizations

The analysis covers the following areas:

### 1. **Accident Hotspots**
   - Using latitude and longitude, accidents are visualized on a map to show high accident density areas.
   - A heatmap is generated using `Folium` to visualize accident hotspots.

### 2. **Time of Day Analysis**
   - Accidents are analyzed based on the time of occurrence. Trends are visualized using bar charts for:
     - **Hour of the day**
     - **Day of the week**
     - **Month of the year**

### 3. **Weather and Road Conditions Impact**
   - The relationship between weather conditions and accident severity is analyzed and visualized.
   - Road conditions like dry, wet, and icy roads are considered to analyze their impact on accident frequency.

### 4. **Correlations Between Variables**
   - A heatmap is generated to show correlations between accident severity, time of day, weather, and road conditions.
