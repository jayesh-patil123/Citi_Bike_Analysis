# Citi_Bike_Analysis
# Citi Bike Data Analysis (2025)

🚴‍♂️ This project analyzes Citi Bike trip data (Jan–Apr 2025, Jersey City) to explore usage trends, rider behavior, and operational insights.  
It demonstrates a full **data analysis pipeline** — from raw data cleaning to business-driven insights.

---

## 📂 Project Workflow
1. **Data Collection & Cleaning**
   - Combined multiple monthly datasets (~100K+ records).
   - Converted timestamps, engineered trip duration, and handled missing station data.

2. **Exploratory Data Analysis (EDA)**
   - Distribution of trip durations.
   - Trips by hour of day & day of week.
   - Member vs casual user behavior.
   - Top start/end stations and station-to-station flows.

3. **Visualization**
   - Static plots: Matplotlib & Seaborn.
   - Interactive charts: Plotly.

4. **Insights**
   - Members take shorter, frequent trips (commuting), while casual users take longer leisure rides.
   - High-demand routes identified for better bike allocation and maintenance planning.
   - Peak hours and weekdays show operational pressure points.

---

## 📊 Key Deliverables
- Cleaned dataset (`citi_bike_cleaned_2025.csv`)
- Analysis notebook (`citi_bike_analysis.ipynb`)
- Visualizations (static + interactive)
- Business recommendations for operations and user engagement

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy)
- Visualization: Matplotlib, Seaborn, Plotly
- Jupyter Notebook
