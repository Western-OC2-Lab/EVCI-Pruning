# EVCI-Pruning
With the increasing demand for real-time processing on IoT devices, optimizing machine learning models' size, latency, and efficiency is crucial. This repository implements pruning techniques to improve computational efficiency in resource-constrained environments, specifically targeting Electric Vehicle Charging Infrastructure (EVCI).

# Project Overview
This project focuses on optimizing machine learning models for anomaly detection in resource-constrained EVCI environments. Using the CICEVSE2024 dataset, we trained and optimized three models—Multi-Layer Perceptron (MLP), Long Short-Term Memory (LSTM), and XGBoost—by applying Optuna for hyperparameter tuning and SHAP for feature selection. The final models were pruned and converted to CSR (Compressed Sparse Row) format, achieving significant reductions in model size and inference time while retaining robust anomaly detection performance.

# Dataset
Two primary datasets, Final_EVSE_A.csv and Final_EVSE_B.csv, are included for benchmarking and further research. These datasets were used for model training and evaluation, providing a foundation for future research in EVCI anomaly detection.
