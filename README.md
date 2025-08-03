# 🌾 Smart Farm Irrigation System

This project is a Smart Sprinkler Predictor built using **Python**, **Streamlit**, and **scikit-learn**. The model uses 20 sensor readings to predict whether the sprinkler for `parcel_0` should be ON or OFF based on trained data.

---

## 🚀 Features

- 🌡️ Takes 20 real-time scaled sensor inputs (0–1).
- 🤖 Uses a trained Linear Regression model to predict sprinkler status.
- ✅ Provides easy-to-understand ON/OFF prediction.
- 🌐 Simple web interface built with Streamlit.

---

## 📁 Files Included

| File                          | Description                                      |
|------------------------------|--------------------------------------------------|
| `app.py`                     | Streamlit web app for sensor input and prediction |
| `Farm_Irrigation_System.pkl` | Trained machine learning model                   |
| `README.md`                  | Project documentation                            |

---

## 📊 Model Overview

- **Algorithm Used**: Linear Regression
- **Input**: 20 sensor values (scaled between 0 to 1)
- **Output**: Float prediction for `parcel_0` (typically interpreted as ON if ≥ 0.5)

---

## 🛠️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/smart-irrigation-app.git
   cd smart-irrigation-app
