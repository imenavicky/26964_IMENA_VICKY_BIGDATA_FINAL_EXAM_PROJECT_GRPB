# 🌍 Earthquake Data Analysis and Clustering

## 👤 Author

- ## IMENA VICKY
- ## ID: 26964
- INTRO TO BIG DATA Capstone Project 2025  
- Lecturer: Eric Maniraguha

This capstone project analyzes global earthquake data from the US Geological Survey (USGS) using Python and Power BI. It identifies seismic activity patterns and clusters earthquakes based on location, magnitude, and depth.

---

## 📁 Project Structure
📦 Earthquake-Analysis
├── 📊 Earthquake_Dashboard.pbix
├── 📓 Earthquake_Analysis.ipynb
├── 📁 /data
│ └── earthquakes_clean.csv


---

## 🎯 Problem Statement

Can we use clustering to identify earthquake hotspots based on magnitude, depth, and location?

This project uses near real-time data from USGS (magnitude 2.5+ from the past 30 days) to detect patterns, perform machine learning clustering, and visualize insights interactively.

---

## 📊 Dataset

- **Source:** [USGS Earthquake Data](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/2.5_month.csv)
- **Format:** CSV (structured)
- **Features:** `latitude`, `longitude`, `depth`, `mag`, `place`, `time`, and more
- **Rows after cleaning:** ~1,654

---

## 🧪 Python Tasks (Jupyter Notebook)

- ✅ Data Cleaning (missing values, outliers)
- ✅ Exploratory Data Analysis (EDA)
- ✅ Feature Engineering: `mag_class` column (Minor, Moderate, Strong)
- ✅ K-Means Clustering (grouped into 4 seismic clusters)
- ✅ Evaluation using Silhouette Score
- ✅ Exported cleaned dataset to CSV for Power BI

---

## 📈 Power BI Dashboard

### Key Visuals:
- 🌐 **Map**: Earthquake locations by cluster and magnitude
- 📊 **Bar Chart**: Earthquake count by `mag_class` or `type`
- 📈 **Line Chart**: Earthquakes over time
- 💥 **Scatter Plot**: Relationship between depth and magnitude
- 📦 **Histogram**: Magnitude distribution using binning
- 🧩 **Slicers**: Filter by `cluster`, `type`, or `mag_class`

---

## 📸 Dashboard Screenshot

<img width="1027" height="592" alt="image" src="https://github.com/user-attachments/assets/9b8cecf2-e3da-45c7-8bfa-e1bc9ccce7fb" />

---

## 💡 Key Insights

- Earthquake clusters reveal geographic hotspots
- Most earthquakes in the dataset are moderate in strength
- Deeper quakes do not always correlate with stronger magnitudes
- Time trends show bursts of activity on certain days

---

## 🛠️ Tools Used

- Python
- Jupyter Notebook
- Power BI Desktop
---

## 🔐 Academic Integrity

This is an original academic project submitted for evaluation. All work is my own and complies with AUCA’s academic honesty policy.

---

## 🙏 Acknowledgements

- USGS for providing open earthquake datasets  
- Power BI and Python open-source libraries  

---

## ✅ Conclusion

This project demonstrates the power of combining data science and visualization tools to understand global earthquake activity. Through data cleaning, clustering, and interactive dashboarding, we uncovered meaningful patterns such as seismic hotspots, depth-magnitude relationships, and temporal trends in earthquake occurrences.

By leveraging Python for analytics and Power BI for communication, the project provides both technical depth and accessible insights for decision-makers or researchers. This approach can be extended to other environmental or geospatial challenges for even broader impact.
