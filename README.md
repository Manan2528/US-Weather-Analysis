🧩 Problem Statement:
Weather plays a big role in our daily lives, from travel and farming to health and safety. This project studies weather data from different places in the United States to find patterns and trends. 
By analyzing things like temperature, wind speed, humidity, and weather conditions, we can better understand how the weather changes over time and across locations. 
This helps in making smarter decisions for the future based on real data.

## 📁 Dataset Overview

**🔗 Dataset Link**: [US Weather Events Dataset](https://drive.google.com/file/d/1ISt0vNAAh7Ry1hco-PJsiAZQ5hwWeh_C/view?usp=sharing)

The dataset contains detailed records of weather events with the following columns:

- `EventId`: Unique ID for each weather event
- `Type`: Type of weather event (e.g., Snow, Fog)
- `Severity`: Event severity (e.g., Light, Severe)
- `StartTime(UTC)` & `EndTime(UTC)`: Start and end times in UTC
- `Precipitation(in)`: Amount of precipitation in inches
- `TimeZone`: Time zone of the event
- `AirportCode`: Nearest airport code
- `LocationLat`, `LocationLng`: Latitude and Longitude
- `City`, `County`, `State`, `ZipCode`: Location details

📌 **Example**:  
Most events in the dataset occur in Saguache, Colorado (CO), near airport `K04V`, often classified as Snow or Fog.

---

## 📓 Notebook Details

**File**: `US_Weather_data_analysis.ipynb`

The notebook includes:
- Data cleaning and preprocessing
- Date-time parsing and event duration calculation
- Analysis of weather types and severity
- Visualizations of event frequency and geographic spread

---


## 🛠️ Tools & Libraries Used

- **Python 3.x**
- **Jupyter Notebook**
- **Pandas** for data handling
- **Matplotlib & Seaborn** for visualizations
- **Datetime** for time and duration analysis

---

⭐️ *If you found this project helpful, please consider starring the repository!*
