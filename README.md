# Predictive Maintenance using Remaining Useful Life (RUL) Prediction

## Overview

Predictive maintenance is a critical application of machine learning in industrial systems.  
This project predicts the **Remaining Useful Life (RUL)** of mechanical components using sensor data.

The system analyzes time-series sensor readings from machinery and predicts when equipment is likely to fail, allowing maintenance before breakdown occurs.

Datasets used:
- NASA C-MAPSS FD001 dataset
- PRONOSTIA bearing dataset

---

## Objectives

- Process and analyze industrial sensor data
- Build predictive models for RUL estimation
- Compare model performance across datasets
- Develop a scalable predictive maintenance pipeline

---

## Datasets

### NASA C-MAPSS
Simulated turbofan engine degradation dataset used for RUL prediction.

Features include:
- Operational settings
- Multiple sensor measurements
- Engine cycles until failure

### PRONOSTIA
Bearing degradation dataset used for machine prognostics.

---

## Project Pipeline

1. Data Loading and Validation
2. Data Preprocessing
3. Feature Engineering
4. Model Training
5. Model Evaluation
6. Performance Analysis

---

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## Project Structure
- Predictive-Maintenance-RUL-Prediction
- │
- ├── data
- ├── notebooks
- ├── src
- ├── models
- ├── results

---

## Results

The trained models predict equipment failure cycles and estimate remaining useful life based on historical sensor data.

This approach enables **early fault detection and predictive maintenance planning** in industrial systems.

---

## Applications

- Manufacturing equipment monitoring
- Aircraft engine maintenance
- Industrial IoT systems
- Smart factories

---

## Future Improvements

- Deep Learning models (LSTM / Transformer)
- Real-time streaming prediction
- Deployment using APIs
- Integration with IoT monitoring systems

---

## Author

Prathish A  
