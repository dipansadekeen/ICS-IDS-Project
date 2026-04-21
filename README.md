# Intrusion Detection for Industrial Control Systems

---

## Project Overview
This project focuses on detecting cyber-physical attacks in Industrial Control Systems (ICS) using machine learning and deep learning techniques. The study is conducted on the WADI (Water Distribution) dataset, which simulates real-world water system operations.

The approach leverages:
- Time-series windowing
- Unsupervised learning (benign-only training)
- Semi-supervised learning (few-shot attack data)
- Threshold-based anomaly detection

---

## Objectives
- Learn normal system behavior from sensor data  
- Detect anomalies representing cyber-attacks  
- Compare multiple ML/DL models  
- Evaluate performance using standard metrics  

---

## Models Implemented
- **Isolation Forest **
- **LSTM Autoencoder (Unsupervised)**
- **LSTM Autoencoder (Semi-Supervised)**
- **Transformer Autoencoder (Semi-Supervised)**

---

## Threat Model
- Attackers manipulate sensor readings or control signals  
- Training data is mostly benign  
- Attack data is rare and partially labeled  
- Detection is based on deviation from learned normal patterns  

---

## How to run
- This project was run in Google Colab 
- Locally, set the dataset location in path and run cell by cell.

---

## Datasets
Dataset is collected from iTrust https://itrust.sutd.edu.sg/itrust-labs-home/itrust-labs_wadi/ 
Dataset Identification: Wadi A2 2019 dataset WADI_dataset_new.csv, WADI_attackdataLABLE.csv

---

### Requirements
pip install numpy pandas torch scikit-learn matplotlib seaborn

---

### Contributors:
Dipan Sadekeen
Jesse Trueba // jtrue011@fiu.edu
Marco Perez // mpere1261@fiu.edu

