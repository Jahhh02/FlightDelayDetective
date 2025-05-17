# ✈️ FlightDelayDetective

**FlightDelayDetective** is a data pipeline and machine learning project that predicts U.S. flight delays using historical **FAA** and **weather datasets**. The project joins and cleans large-scale datasets, applies feature engineering, and deploys a predictive model. A dashboard presents delay trends by airport and airline to provide actionable insights.

---

## 📌 Features

- 🧹 **Data Cleaning**:
  - Handles missing and inconsistent data
  - Filters out canceled or diverted flights
- 🔗 **Data Integration**:
  - Merges FAA flight data with historical weather records
  - Time-based and geolocation-based joins
- 🧠 **ML Modeling**:
  - Binary classification model to predict flight delays
  - Feature selection and hyperparameter tuning
- 📊 **Dashboard Visualization**:
  - Delay trends by airport, airline, and weather conditions
  - Interactive charts for exploring flight patterns

---

## 🛠️ Tech Stack

- **Data Processing**: Pandas, PySpark (optional for large data)
- **Machine Learning**: scikit-learn, XGBoost
- **Visualization**: Streamlit or Dash
- **Data Sources**:
  - FAA flight delay dataset
  - NOAA or OpenWeatherMap for weather data
- **Storage**: Local CSVs or cloud object storage (S3, GCS)

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- pip or conda for package management
- Jupyter Notebook (optional for EDA)

### Installation

```bash
git clone https://github.com/Jahhh02/FlightDelayDetective.git
cd FlightDelayDetective
pip install -r requirements.txt
