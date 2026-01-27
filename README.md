# 🚁 Drone Battery State of Health (SOH) Prediction

An AI-powered system designed to estimate the **State of Health (SOH)** of Lithium-Ion drone batteries. By accurately predicting battery degradation, this tool helps prevent mid-flight power failures and optimizes maintenance schedules.

## 🔋 Problem Statement
Drone batteries degrade over time due to charge cycles, temperature changes, and usage patterns. A sudden drop in battery health can lead to:
* **Catastrophic Failures:** Drones falling mid-flight.
* **Inefficient Operations:** Reduced flight time and reliability.
* **Safety Risks:** Fire hazards from damaged cells.

This project uses Machine Learning to predict the **SOH percentage** based on real-time sensor data (Voltage, Current, Temperature).

## 🚀 Key Features
* **📊 Data Analysis:** Visualization of battery discharge curves and capacity fade over time.
* **🤖 Advanced Modeling:** Implements **XGBoost Regressor** for high-accuracy prediction.
* **📉 Error Analysis:** Evaluates model performance using RMSE (Root Mean Squared Error) and R² Score.
* **🔌 Scalable:** Can be adapted for EV (Electric Vehicle) battery management systems (BMS).

## 🛠️ Tech Stack
* **Language:** Python 3.x
* **Machine Learning:** XGBoost, Scikit-Learn
* **Data Processing:** Pandas, NumPy
* **Visualization:** Matplotlib, Seaborn
* **Development:** Jupyter Notebook

## 📂 Project Structure
```bash
Drone-Battery/
├── data/                  # Dataset files (csv/xlsx)
├── notebooks/             # Jupyter Notebooks for training & analysis
│   └── Drone Battery.ipynb
├── .gitignore             # Files to exclude (venv, large data)
├── requirements.txt       # Dependencies list
└── README.md              # Project Documentation
