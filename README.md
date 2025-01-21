Air Quality Analysis Portal 🌍
Overview
A comprehensive web application for analyzing and predicting Air Quality Index (AQI) using real-time data from the Central Pollution Control Board (CPCB) of India. The application provides both predictive capabilities and detailed data analysis tools.
🌟 Features
1. AQI Predictor

Instant AQI predictions using key pollutant measurements
Based on machine learning model trained on CPCB data
Health recommendations based on predicted AQI
User-friendly interface for entering pollutant values

2. Data Analysis Dashboard

Upload and analyze air quality datasets
Interactive data visualization tools
Statistical analysis capabilities
Feature-rich exploration of AQI trends

📊 Data Source

Real-time hourly data from various locations across India
Data sourced from official CPCB website: CAAQM Dashboard
Dataset period: June 2023 to January 2025
Data includes various pollutant measurements and AQI calculations

🛠️ Tech Stack

Python
Streamlit
Scikit-learn
Pandas
Plotly Express
NumPy

⚙️ Installation & Setup

Install required packages

bashCopypip install -r requirements.txt

Run the application

bashCopystreamlit run Home.py
📁 Project Structure
Copyyour_project_folder/
│
├── Home.py                # Landing page
├── requirements.txt       # Package dependencies
├── Data.csv              # CPCB dataset
│
├── pages/
│   ├── 1_AQI_Predictor.py    # AQI prediction interface
│   ├── 2_Data_Analysis.py    # Data analysis dashboard
│
└── utils/
    └── model.py          # ML model utilities
🚀 Live Demo
Visit our deployed application: Air Quality Analysis Portal
📝 Machine Learning Model

Random Forest Regressor
Features used: PM2.5, PM10, NO2, CO, SO2
Model trained on historical CPCB data
Optimized hyperparameters for better accuracy

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check issues page.


🙏 Acknowledgments

Central Pollution Control Board (CPCB) for providing the data
data.gov.in for data accessibility
Streamlit for the amazing web framework

📊 Data Reference
The AQI data is sourced from the Central Pollution Control Board's Continuous Ambient Air Quality Monitoring System (CAAQMS). The dataset contains hourly readings from June 2023 to January 2025, providing comprehensive air quality measurements across various Indian locations.
For the latest data, visit: CPCB CAAQM Dashboard
