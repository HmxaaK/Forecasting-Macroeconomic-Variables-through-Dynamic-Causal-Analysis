
---

# 📊 Macroeconomic Variable Forecasting Dashboard

This project aims to forecast key **macroeconomic variables** and study their **causal dynamics** using a combination of **Econometrics, Machine Learning, and Power BI**.
The dashboard is being developed iteratively, starting with **Consumption** as the first variable.

---

## 🚀 Project Overview

* **Phase 1 (Current Progress):**

  * Built **one-step-ahead consumption forecasts** using `statsmodels` in Python.
  * Implemented **AR (Autoregressive)** and **ARDL (Autoregressive Distributed Lag)** models.
  * Integrated results into a **Power BI dashboard** for visualization.
  * Evaluated baseline accuracy using **Residuals & RMSE**.

* **Planned Phases (Future Work):**

  * Extend models to **VAR (Vector Autoregression)** and **VECM (Vector Error Correction Model)** for multivariate causal analysis.
  * Apply **Machine Learning models** (XGBoost, LightGBM, LSTM/GRU) for nonlinear forecasting.
  * Incorporate **Causal Analysis**:

    * Granger causality
    * Impulse Response Functions (IRFs)
    * SHAP values for ML interpretability
  * Expand dashboard to cover additional variables:

    * **GDP**
    * **Inflation (CPI)**
    * **Unemployment**
    * **Interest Rates**

---

## 🛠️ Tech Stack

* **Python** (Statsmodels, Pandas, NumPy, Scikit-learn, XGBoost, Darts, DoWhy)
* **Power BI** (Data modeling, Forecast visualization, Interactive dashboards)
* **Data Sources:** FRED, World Bank, IMF, OECD

---

## 📈 Dashboard Features

* Visualize **actual vs forecasted consumption**.
* Compare models (**AR, ARDL, VAR, ML**).
* Evaluate accuracy metrics (RMSE, MAE, MAPE).
* Explore **causal dynamics**: how GDP, inflation, or interest rate shocks affect consumption.
* Scenario simulation: “What if inflation increases by 1%?”

---

## 📂 Repository Structure

```
├── data/                # Raw and processed macroeconomic datasets
├── notebooks/           # Jupyter notebooks for EDA, forecasting, causal analysis
├── models/              # Python scripts for AR, ARDL, VAR, ML models
├── powerbi/             # Power BI dashboard files (.pbix)
├── results/             # Forecast outputs, residuals, model evaluation
└── README.md            # Project documentation
```

---

## 📊 Example Dashboard Snapshot

<img width="1009" height="585" alt="image" src="https://github.com/user-attachments/assets/4bd5df8b-6e83-4056-9c09-9a1a49c7f88d" />


---

## 🔮 Roadmap

* [x] Implement AR & ARDL forecasts for Consumption
* [x] Build Power BI dashboard for Consumption forecasts
* [ ] Add VAR & VECM models
* [ ] Integrate ML models (XGBoost, LightGBM, LSTM)
* [ ] Add causal analysis (Granger, IRF, SHAP)
* [ ] Expand dashboard to GDP, Inflation, Unemployment, Interest Rates
* [ ] Deploy interactive dashboard for public access

---
