# 🔆 Solar Energy Prediction using SL Transformer and LSTM

Exploring Time-Series Forecasting with Two Powerful Deep Learning Models —**Spatial-Temporal Transformer (SL Transformer)** and **LSTM (Long Short-Term Memory)**—to predict solar energy generation using historical and weather data. The SL Transformer is designed to handle both **short-term (next 6 hours)** and **long-term (next few months)** predictions, while LSTM is used as a baseline model for comparison.

---

## 📌 Project Overview


This project builds a **dual-scale solar energy forecasting system** using cutting-edge deep learning models:

> 🔹 A **Spatial-Temporal Transformer (SL Transformer)** that captures both local fluctuations and long-term seasonal patterns  
> 🔸 An **LSTM model** that serves as a traditional baseline for long-range forecasting

Whether it's predicting the next **6 hours** or the next **6 months**, this system translates solar trends into actionable insights — ideal for smart grids, green energy systems, and future-ready infrastructure.

---

## 🧠 Models Breakdown

### 🔮 SL Transformer
- Built for **multi-horizon forecasting**.
- Captures **spatial** and **temporal** dependencies using attention mechanisms.
- Predicts:
  - ✅ Next 6 hours (real-time applications)
  - ✅ Next few months (seasonal trend analysis)

### ⏳ LSTM
- Handles **sequential dependencies** over long ranges.
- Used for **long-term solar trend prediction**.
- Serves as a **baseline** for benchmarking the Transformer model.

---

## 🛰️ Dataset

- 📂 Location: [`/data`](https://github.com/cosmicc0der78/SolarEnergyPrediction/SolarPrediction.csv)
- ✅ Features:
  - Solar irradiance components 
  - Meteorological variables (temperature, humidity, wind speed)

---

## 📈 Performance Metrics

| Model            | MSE (kWh)  | MAE (kWh) |
|------------------|------------|-----------|
| LSTM             | 0.0015     | 0.0157    | 
| SL Transformer   | 0.0067     | 0.0469    | 

> While LSTM demonstrates stronger performance on long-term forecasting with lower error metrics, the SL Transformer stands out for its ability to generalize across both short-term (next 6 hours) and long-term (next few months) predictions within a single architecture.
It captures temporal dependencies and spatial dynamics, making it more scalable and adaptive for real-world solar energy systems where conditions change rapidly. Its ability to learn complex spatial-temporal patterns makes it highly adaptable for real-time energy management, grid optimization, and scalable deployment in smart energy systems.

---

## 🧰 Tech Stack

- 🐍 Python 3.12
- 📦 TensorFlow / PyTorch
- 📊 Pandas, NumPy, Scikit-learn
- 📈 Matplotlib, Seaborn
- 🚀 Google Colab (for training + inference)

---

## 📫 Contact

**Indu Sree.N**  
📧 [indusreen78@gmail.com](mailto:indusreen78@gmail.com)  
🐙 [GitHub](https://github.com/cosmicc0der78)  

> If you have ideas, suggestions, or just want to connect—feel free to reach out!
