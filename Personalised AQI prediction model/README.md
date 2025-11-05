# Integrating Environmental Data with CNN-LSTM Models for AQI Prediction

### Overview
This project predicts Air Quality Index (AQI) using deep learning (CNN-LSTM) by integrating temperature, rainfall, and wind data.  
It also computes a Composite Health Impact Score (CHIS) and a Personalized Health Risk Score (PHRS) based on user health conditions.

### Features
- Data Cleaning and Standardization across multiple sources (CPCB, IMD)
- CNN-LSTM model for AQI time-series prediction
- Personalized health risk computation
- Prescriptive analytics for activity recommendations
- Exports results in CSV and JSON formats

### Tech Stack
`Python`, `TensorFlow`, `scikit-learn`, `pandas`, `NumPy`, `Jupyter`

### Files Included
- `aqi_prediction_notebook.ipynb` – full model + explanation
- `*_data.csv` – cleaned datasets
- `deep_learning_predictions.csv` – final predictions
- `personalized_summary.csv/json` – personalized output
- `ML report.pdf` – documentation

### How to Run
1. Open `aqi_prediction_notebook.ipynb` in Jupyter.
2. Run all cells in order (Cells 1–6).
3. Follow Cell 5 to input your health details and get predictions.
4. Cell 6 will export your results to CSV and JSON.



Author: **Ethin Seerla**  
VIT Vellore | B.Tech CSE (2022–2026)
