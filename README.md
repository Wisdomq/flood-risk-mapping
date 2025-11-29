# flood-risk-mapping

# Flood Risk Mapping Using Deep Learning & Climate Datasets

This project builds a deep learning pipeline to predict and map flood risk using multi-source climate data, including rainfall (`rain.nc`), temperature (`t.nc`), and historical extreme-precipitation events. It integrates geospatial processing, computer vision models, and temporal analysis to support climate adaptation and disaster risk planning.

## 🚀 Overview

This work models the relationship between climatic drivers and flood risk using:
- Convolutional Neural Networks (CNNs)
- Time-series feature extraction
- Climate datasets from 1951–2010 (historical) and +2K / +4K warming scenarios
- High–resolution (5 km) downscaled annual maximum 72-hr rainfall events

The output is a spatial flood risk map and prediction model supporting future risk assessment.


## 🧠 Model Summary
- **Input A:** Temperature (`t.nc`)
- **Input B:** Rainfall (`rain.nc`)
- **Architecture:** Custom Complex CNN (`zh_net`)
- **Output:** Flood-risk prediction over 221×171 grid  
- **Performance:**
  - Accuracy: **81.92%**
  - MAE: **0.476**
  - R² score: **0.693**

## 🛠️ Tech Stack
- Python  
- TensorFlow / PyTorch  
- NumPy, Pandas  
- NetCDF4 / xarray  
- Matplotlib & Seaborn  
- Geospatial visualization tools

📊 Results

Outputs include:

-Flood risk heatmaps
-Threshold-based rainfall categories (high/medium/low)
-Model comparison metrics


