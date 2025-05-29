
# 🔮 LSTM-Based Time Series Forecasting for Energy Consumption

This repository demonstrates a deep learning approach to **forecast hourly electricity consumption** using **Long Short-Term Memory (LSTM)** networks. The project uses historical data from two major U.S. power utilities — **AEP** and **DOM** — and provides a hands-on example of time series prediction using neural networks.

---

## 📝 Project Description

This project uses LSTM networks to forecast hourly energy consumption from AEP and DOM datasets. It includes data preprocessing, model building, training, and evaluation with visualizations. Ideal for learning time series forecasting using deep learning techniques like LSTM in a real-world energy context and compares it with RNN prediction with the same data.

---

## 📈 Outputs

R2 Score of RNN model =  0.9394322226943517
R^2 Score of LSTM model =  0.9503250585427323 

---
## 📊 Data Sources

- **AEP (American Electric Power):**  
  Hourly electricity demand data from AEP, a major electric utility in the U.S. Midwest and South.

- **DOM (Dominion Energy):**  
  Hourly consumption data from Dominion Energy, serving the eastern U.S. including Virginia and North Carolina.


## 🚀 How to Run

1. Clone the repo:
```bash
git clone https://github.com/yourusername/LSTM-Energy-Forecasting.git
cd LSTM-Energy-Forecasting
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Launch the notebook:
```bash
jupyter notebook LSTM.ipynb
```

---

## 🛠️ Tech Stack

- Python
- NumPy, Pandas, Matplotlib
- Scikit-learn
- TensorFlow / Keras (LSTM, Dropout, Dense layers)

---

## ✅ Results

- Forecasts energy demand with good accuracy
- Uses R² score for model evaluation
- Visual comparison of predicted vs actual values

---

## 📸 Visuals

- Trend analysis of energy demand
- Predicted vs actual comparison plots
- Model architecture summary

