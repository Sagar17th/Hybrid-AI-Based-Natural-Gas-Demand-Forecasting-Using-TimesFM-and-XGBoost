# Hybrid AI-Based Natural Gas Demand Forecasting Using TimesFM and XGBoost

A hybrid AI-driven time-series forecasting framework for monthly natural gas demand prediction using Google's TimesFM foundation forecasting model and XGBoost regression.

---

# Overview

This project presents a hybrid forecasting architecture that combines the strengths of:

- TimesFM Foundation Model
- XGBoost Regression Model

The system is designed to improve forecasting accuracy by leveraging:
- Temporal pattern learning
- Seasonal trend analysis
- Feature engineering
- Ensemble forecasting

The project focuses on monthly natural gas demand forecasting using historical time-series data.

---

# Key Features

- Hybrid AI forecasting framework
- Monthly time-series forecasting
- Feature engineering pipeline
- Lag and rolling statistical features
- Ensemble prediction architecture
- Residual and trend analysis
- Visualization of forecasting performance
- Research/publication-ready workflow

---

# Technologies Used

## Programming Language
- Python

## Libraries & Frameworks
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost
- TimesFM

---

# Project Architecture

The forecasting pipeline consists of the following stages:

```text
Input Dataset
      ↓
Data Preprocessing
      ↓
Feature Engineering
      ↓
 ┌─────────────────────┬─────────────────────┐
 │                     │                     │
TimesFM Model      XGBoost Model
 │                     │
Forecast           Prediction
 └──────────┬──────────┘
            ↓
     Hybrid Ensemble
            ↓
      Final Forecast
            ↓
 Evaluation & Visualization
```

---

# Dataset

The dataset contains:
- Monthly natural gas consumption records
- Historical time-series observations

## Dataset Characteristics
- Monthly granularity
- Chronologically ordered
- Used for supervised forecasting

---

# Data Preprocessing

The preprocessing pipeline includes:
- Missing value handling
- DateTime conversion
- Chronological sorting
- Null removal
- Train-test split
- Data normalization

---

# Feature Engineering

Feature engineering plays a major role in improving forecasting accuracy.

## Temporal Features
- Year
- Month
- Quarter

## Lag Features
- Lag 1 (previous month)
- Lag 6
- Lag 12

## Rolling Features
- Rolling Mean
- Rolling Standard Deviation

These features help the model capture:
- Seasonal behavior
- Historical dependencies
- Local trends
- Demand fluctuations

---

# Models Used

## 1. TimesFM Foundation Model

TimesFM is used for:
- Long-term dependency learning
- Seasonal trend forecasting
- Sequence modeling

### Advantages
- Strong temporal learning capability
- Handles long forecasting horizons
- Learns generalized time-series patterns

---

## 2. XGBoost Regression Model

XGBoost is used for:
- Nonlinear forecasting
- Feature-based learning
- Gradient boosting prediction

### Advantages
- High prediction accuracy
- Robust against overfitting
- Fast training performance

---

# Hybrid Ensemble Framework

The outputs from TimesFM and XGBoost are combined using an ensemble strategy to generate the final forecast.

## Benefits of Hybridization
- Improved forecasting accuracy
- Better seasonal learning
- Reduced prediction error
- Robust forecasting performance

---

# Evaluation Metrics

The forecasting system is evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Square Error)
- MAPE (Mean Absolute Percentage Error)
- R² Score

---

# Visualizations

The project includes:
- Actual vs Predicted plots
- Forecast trend graphs
- Residual error plots
- Rolling statistics analysis

---

# Installation

## Clone Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

## Navigate to Project Folder

```bash
cd your-repository-name
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Running the Project

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run:

```text
new-sagar-final.ipynb
```

---

# Project Structure

```text
├── data/
├── notebooks/
├── plots/
├── models/
├── README.md
├── requirements.txt
└── new-sagar-final.ipynb
```

---

# Results

The hybrid forecasting model demonstrated:
- Improved forecasting accuracy
- Better seasonal trend learning
- Stable future predictions
- Lower forecasting error compared to standalone models

---

# Future Scope

Possible future improvements include:
- Real-time forecasting
- Weather data integration
- Transformer-based ensembles
- Cloud deployment
- IoT-enabled forecasting systems

---

# Research Contribution

This project demonstrates how foundation models like TimesFM can be integrated with machine learning algorithms such as XGBoost for improved energy demand forecasting.

The hybrid framework provides:
- Better generalization
- Improved temporal learning
- Enhanced forecasting stability

---

# Author

Sagar Verma  
Department of Information Technology  
National Institute of Technology Srinagar

---

# License

This project is intended for academic and research purposes.
