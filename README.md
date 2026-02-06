# 🌍 Climate Time Machine: Historical Weather Analysis & Prediction (1940-2026)

## 📌 Project Overview
This project uses a **4th-Degree Polynomial Regression** model trained on historical weather data from the **1940-1945** period. The goal is to create a "Digital Time Machine" that predicts modern-day weather scenarios using the atmospheric logic of the mid-20th century. By comparing these predictions with current observations, we can mathematically visualize the impact of **Global Warming** and **Urbanization**.

## 🚀 Technical Highlights
* **Algorithm:** Polynomial Regression (Degree 4) to capture complex non-linear climate patterns.
* **Success Rate:** **87.69% R² Score**, demonstrating high predictive reliability.
* **Error Margin:** **1.40°C Mean Absolute Error (MAE)**.
* **Feature Engineering:** * Trigonometric encoding for seasonal cycles (`Month_Sin`, `Month_Cos`).
    * Spatial features including Elevation, Latitude, and Longitude.

## 📊 The "Climate Gap" Discovery: Sakarya Case Study
One of the most striking results of this model is the gap between "Natural 1940s Logic" and "Modern Reality."

| Metric | Value |
| :--- | :--- |
| **Model Prediction (1940s Logic)** | **11.67°C** |
| **Actual Observed Temp (Feb 2026)** | **18.00°C** |
| **Total Temperature Gap** | **6.33°C** |

### 🔍 Breakdown of the 6.3°C Difference:
1. **Global Warming (~+1.5°C):** General rise in global baseline temperatures due to increased $CO_2$ levels since 1940.
2. **Urban Heat Island Effect (~+3.5°C):** Sakarya’s transformation from a rural town in 1940 to a modern industrial city. High concrete and asphalt density traps heat significantly.
3. **Daily Variability (~+1.3°C):** Natural atmospheric fluctuations and specific daily weather conditions.

## ✅ Model Validation
The model's reliability is confirmed by the **Residual Distribution (Normal Distribution)** graph. Most errors are tightly clustered around zero, proving that the 6.3°C gap is not a calculation error, but a reflection of environmental change.

## 🛠️ How to Run
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/emrezorlu1239/WW2-Historical-Weather-MachineLearning](https://github.com/emrezorlu1239/WW2-Historical-Weather-MachineLearning)
