# 🔮 AutoProphet – Interactive Time Series Forecasting App

![AutoProphet Logo](./AutoProphet.png)

AutoProphet is an interactive and automated **time series forecasting application** built with **Streamlit** and **Meta’s Prophet** library.  
It provides an intuitive web interface for exploring, modeling, and forecasting time series data without writing any code.

---

## 🚀 Features

- 📂 **CSV Uploads** – Import your own time series dataset directly
- ⚙️ **Custom Prophet Configuration** – Adjust growth, seasonality, and changepoint parameters
- 📊 **Interactive Visualizations** – Plot forecasts, trends, and uncertainty intervals using Plotly and Altair
- 🧮 **Model Validation** – Evaluate forecast accuracy with metrics like RMSE and MAE
- 🔧 **Hyperparameter Tuning** – Experiment with Prophet parameters in real time
- 💾 **Export Results** – Save forecast data and configuration files for future analysis

---

## 🧠 Tech Stack

- **Frontend:** Streamlit
- **Modeling:** Prophet (by Meta)
- **Visualization:** Plotly, Altair
- **Data Handling:** Pandas, NumPy
- **Environment:** Python 3.9+

---

## 📦 Installation

Clone this repository and install dependencies:

```bash
git clone https://github.com/VRAJ2202/AutoProphet.git
cd AutoProphet
pip install -r requirements.txt
```

---

## 🧮 Usage

Run the Streamlit app locally:

```bash
streamlit run AutoProphet.py
```

Then open your browser and navigate to:
```
http://localhost:8501
```

---

## 📁 Repository Structure

```
AutoProphet/
│
├── AutoProphet.py              # Main Streamlit application
├── requirements.txt            # Required Python dependencies
├── sample_forecast.csv         # Example dataset for quick testing
├── prophet.png                 # Prophet framework banner
├── AutoProphet.png             # App logo
└── README.md                   # Project documentation
```

---

## 📊 Example Workflow

1. Upload your dataset (CSV format with Date and Value columns)  
2. Configure Prophet model parameters (growth, changepoints, periods, seasonality)  
3. Run the forecast and visualize trends  
4. Validate results and export forecasts

---

## ⚙️ Requirements

Core dependencies are listed in `requirements.txt`:

```
pandas>=1.5.0
prophet>=1.1.0
holidays>=0.20.0
plotly>=5.0.0
altair>=5.0.0
streamlit>=1.25.0
numpy>=1.21.0
```

Install them via:

```bash
pip install -r requirements.txt
```

---

## 🧩 Example Dataset

A small sample dataset `sample_forecast.csv` is included for demonstration.  
You can replace it with your own dataset — ensure it has at least:

| ds (date) | y (value) |
|------------|-----------|
| 2023-01-01 | 105 |
| 2023-01-02 | 108 |
| 2023-01-03 | 112 |

---

## 🧾 License

This project is licensed under the **MIT License**.

---

© 2025 Vraj Patel. All Rights Reserved.
