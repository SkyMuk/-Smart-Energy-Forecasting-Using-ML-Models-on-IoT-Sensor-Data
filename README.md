# 🔋 Smart Energy Forecasting using ML on IoT Sensor Data

This project explores how machine learning models can forecast energy consumption using IoT sensor data. It supports smarter energy usage, load forecasting, and sustainability planning in smart homes and industrial environments.

## 📌 Overview

- Leverages real-world IoT energy usage data
- Applies regression models to forecast future consumption
- Aims to improve energy efficiency and optimize demand response strategies

## 🧠 Features

- Data preprocessing and cleaning of time-series sensor data
- Feature engineering and exploratory data analysis (EDA)
- Implementation of ML models: 
  - Linear Regression  
  - Random Forest  
  - XGBoost  
- Evaluation using metrics like RMSE, MAE, and R²
- Visualization of model performance and energy trends

## 📁 Project Structure

```
Smart_Energy_Forecasting/
│
├── data/              # Raw and preprocessed datasets
├── notebooks/         # Jupyter notebooks for training and analysis
├── models/            # Saved model files
├── plots/             # Visualization outputs
└── README.md          # Project documentation
```

## 🛠️ Tech Stack

- **Languages:** Python  
- **Libraries:** Scikit-learn, Pandas, NumPy, XGBoost, Matplotlib, Seaborn  
- **Platform:** Jupyter Notebook

## 📊 Use Cases

- Predict high-load hours for energy grid balancing
- Detect anomalies in energy usage for smart homes
- Optimize resource allocation in commercial buildings

## 🚀 Future Improvements

- Add LSTM models for time-series deep learning forecasting  
- Integrate weather or occupancy data for hybrid models  
- Build real-time dashboard using Streamlit

## 📈 Sample Results

- XGBoost model achieved **R² score of 0.89**
- Forecasted daily consumption trends with <10% error margin

## 👩‍💻 Author

This repository was created as part of an AI portfolio showcasing expertise in energy forecasting, machine learning pipelines, and IoT data analytics.

## 📄 License

This project is licensed under the MIT License.
