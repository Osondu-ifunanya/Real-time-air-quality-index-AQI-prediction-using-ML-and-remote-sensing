# 🌬️ Real-time Air Quality Index (AQI) Prediction using Synthetic Data

## 📘 Overview

This project simulates the use of remote sensing and meteorological variables to predict real-time AQI levels using machine learning. It generates synthetic data representing common air quality drivers and trains a Random Forest Regressor to model the relationship.

---

## 🧪 Features

- Generates synthetic features:
  - **Aerosol Optical Depth (AOD)**
  - **Land Surface Temperature (LST)**
  - **Normalized Difference Vegetation Index (NDVI)**
  - **Wind Speed**
- Simulates AQI based on a formula influenced by those inputs
- Trains a machine learning model to predict AQI
- Evaluates model accuracy with R² and RMSE
- Exports dataset to Excel for reproducibility

---

## 🛠 Tools & Libraries

- Python 3
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## 🚀 How to Run

1. **Install dependencies**
   ```bash
   pip install numpy pandas scikit-learn matplotlib
