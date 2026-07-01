# Weather Forecasting and Precision Irrigation using Machine Learning

A Machine Learning and IoT-based precision irrigation system that predicts irrigation requirements using environmental conditions, soil moisture, and real-time weather data. The project integrates a Decision Tree classifier with Arduino-based soil moisture sensing and OpenWeather API to provide crop-specific irrigation recommendations.

This work was published in Springer as part of the ACDIS 2024 conference proceedings.

---

## Features

- Decision Tree-based irrigation prediction
- Real-time weather integration using OpenWeather API
- Arduino soil moisture sensor integration
- Streamlit web application
- Crop-specific irrigation recommendations
- Precision irrigation for multiple crop types
- Real-time decision support

---

## Tech Stack

- Python
- Scikit-learn
- Pandas
- NumPy
- Streamlit
- Matplotlib
- Seaborn
- OpenWeather API
- Arduino Uno
- IoT

---

## Dataset

The dataset contains environmental and agricultural parameters used for irrigation prediction.

Features include:

- Temperature
- Humidity
- Soil Moisture
- Rainfall
- Crop
- Maximum Soil Moisture
- Minimum Soil Moisture
- Pump Status

---

## Model

Algorithm:

- Decision Tree Classifier

Performance:

- Accuracy: **94.12%**

---

## Project Structure

```text
weather-forecasting-precision-irrigation/

├── app/
│   └── streamlit_app.py
│
├── arduino/
│   └── soil_moisture_sensor.ino
│
├── data/
│   └── irrigation_dataset.xlsx
│
├── images/
│
├── notebooks/
│   └── Weather_Forecasting_and_Precision_Irrigation.ipynb
│
├── README.md
├── LICENSE
├── requirements.txt
└── .gitignore
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/weather-forecasting-precision-irrigation.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the Streamlit application

```bash
streamlit run app/streamlit_app.py
```

---

## Workflow

1. Collect soil moisture using Arduino sensors.
2. Fetch live weather data using OpenWeather API.
3. Preprocess environmental data.
4. Predict irrigation requirements using the Decision Tree model.
5. Display irrigation recommendations through the Streamlit dashboard.

---

## Research Publication

**Farming in the Digital Era: Optimizing Crop Yield with Machine Learning and IoT-Driven Weather Forecasting and Precision Irrigation**

Published in Springer Nature (2025)

Conference: ACDIS 2024

---

## Future Improvements

- Random Forest and XGBoost comparison
- Cloud deployment
- Automated irrigation control
- Additional crop support
- Live sensor data streaming
- Mobile application

---

## Author

**Aryaman Modi**

LinkedIn: https://www.linkedin.com/in/aryaman-modi-8a834a200/

GitHub: https://github.com/<your-username>

Email: modiaryaman@gmail.com
