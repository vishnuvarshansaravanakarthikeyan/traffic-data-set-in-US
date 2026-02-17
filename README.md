# 🇺🇸 USA Traffic Dataset (20,000 Rows)

This repository contains a synthetic traffic dataset representing traffic conditions across major cities in the United States.  
The dataset is designed for data analysis, machine learning experiments, visualization practice, and academic projects.

---

## 📂 Dataset Overview

- **Rows:** 20,000
- **Columns:** 10
- **Format:** CSV
- **Time Resolution:** 1-minute intervals
- **Type:** Synthetic (simulated realistic traffic patterns)

---

## 📊 Columns Description

| Column Name        | Description |
|--------------------|------------|
| timestamp          | Date and time of observation |
| city               | US city where traffic was recorded |
| state              | State abbreviation |
| traffic_volume     | Number of vehicles recorded |
| avg_speed_kmh      | Average vehicle speed (km/h) |
| congestion_level   | Traffic congestion category (Low / Medium / High) |
| weather_condition  | Weather during observation |
| incident_type      | Traffic event affecting flow |
| road_type          | Type of road |
| lane_closure       | Whether a lane was closed |

---

## 🌆 Cities Included

- New York  
- Los Angeles  
- Chicago  
- Houston  
- Phoenix  
- Philadelphia  
- San Antonio  
- San Diego  
- Dallas  
- San Jose  

---

## 🌦 Weather Conditions

- Clear  
- Rain  
- Fog  
- Snow  
- Cloudy  

---

## 🚧 Incident Types

- None  
- Accident  
- Construction  
- Breakdown  

---

## 🛣 Road Types

- Highway  
- Urban  
- Rural  
- Expressway  

---

## 💡 Possible Use Cases

- Traffic prediction models  
- Congestion analysis  
- Smart city simulations  
- Machine learning practice  
- Data visualization projects  
- Time series forecasting  
- Anomaly detection  

---

## 🧪 Example Usage (Python)

```python
import pandas as pd

df = pd.read_csv("usa_traffic_dataset_20000_rows.csv")
print(df.head())
print(df.info())
```

---

## 📈 Example Analysis Ideas

- Relationship between weather and congestion
- Speed vs traffic volume correlation
- Incident impact on average speed
- City-wise traffic comparison
- Time-based traffic pattern analysis

---

## ⚠️ Disclaimer

This dataset is **synthetically generated** and does not represent real traffic measurements.  
It is intended only for educational, research, and development purposes.

---

## 📜 License

Free to use for educational and research purposes.

---

## 👨‍💻 Author

Generated for data science practice and experimentation.
