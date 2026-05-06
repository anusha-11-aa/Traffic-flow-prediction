# Traffic-flow-prediction
# Traffic Flow Prediction using Machine Learning & Deep Learning

Developed a time-series forecasting system to predict traffic flow and analyze congestion patterns using Machine Learning and Deep Learning models.

## Problem Statement

Urban traffic congestion leads to delays, increased fuel consumption, and pollution. This project aims to forecast traffic flow in advance to support smarter traffic management and planning.
##  Dataset

- ~48,000+ time-series traffic records  
- Features:
  - Date & Time  
  - Junction ID  
  - Vehicle count  
- Engineered features:
  - Hour, Day, Month, Weekday  

---

## 🔹 Approach

- Performed data preprocessing and feature engineering:
  - Handled missing values  
  - Normalized data  
  - Converted data into time-series sequences  

- Implemented and compared multiple models:
  - Linear Regression  
  - Random Forest  
  - Support Vector Regression (SVR)  
  - XGBoost  
  - LSTM (Deep Learning)

- Designed a hybrid architecture:
  - CNN → captures spatial patterns  
  - BiLSTM → captures temporal dependencies  
  - Residual correction (ARIMA-inspired) → models trends & seasonality  

## Model Details

- Sequence length: 20  
- Multi-layer LSTM architecture  
- Dense layer for final prediction  

## Results

- Achieved ~80% prediction accuracy  
- Evaluated using:
  - Mean Absolute Error (MAE)  
  - Root Mean Square Error (RMSE)  

- Key outcomes:
  - Accurate short-term traffic flow prediction  
  - Identification of peak congestion periods  
  - Hybrid models showed improved performance over standalone models  

---

## Tech Stack

- Python  
- TensorFlow / Keras  
- Scikit-learn  
- Pandas, NumPy  
- Matplotlib  

##  Key Highlights

- Built an end-to-end ML pipeline: preprocessing → modeling → evaluation  
- Applied both traditional ML and deep learning models  
- Designed a hybrid deep learning architecture for improved accuracy  
- Worked with real-world time-series data  

##  Future Scope

- Integrate real-time traffic and weather data  
- Deploy as a web-based prediction system  
- Optimize models using hyperparameter tuning  
