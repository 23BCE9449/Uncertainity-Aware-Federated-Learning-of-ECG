# Uncertainity-Aware-Federated-Learning-of-ECG
# Project Title
Uncertainty-Aware Explainable Federated Learning for Multi-Label ECG Classification

# Overview
This project presents a privacy-preserving framework for multi-label ECG classification using Federated Learning, Explainable Artificial Intelligence (XAI), and Uncertainty Quantification. The framework investigates whether predictive uncertainty can serve as an indicator of explanation consistency across multiple healthcare institutions.

# Key Features
Multi-client Federated Learning
PhysioNet Challenge 2021 ECG Dataset
1D ResNet-34 Architecture
FedAvg, FedProx, and FedAdam
Grad-CAM Explainability
SHAP Feature Attribution
Monte Carlo Dropout Uncertainty Estimation
Cross-Client Explanation Consistency Analysis
Correlation Analysis Between Uncertainty and Explainability

# Dataset
PhysioNet Challenge 2021
Federated Clients:
Chapman-Shaoxing
CPSC-2018
Georgia
Ningbo
PTB-XL

# Final Taxonomy:
AF
IAVB
LAD
LBBB
NSIVCB
NSR
PAC
QAb
RBBB
SB
STach
TAb


# Methodology

<img width="864" height="1189" alt="structure of FL Project" src="https://github.com/user-attachments/assets/cd58b8aa-5a83-4de5-8ad1-c553b734eba4" />

## Repository Structure

```text
ECG-FL-XAI/
├── README.md
├── data/
│   └── sample_data/
├── preprocessing.ipnb
|── label_harmonization.ipnb
|── feature_extraction.ipnb
├── federated_learning.ipnb
├── explainability/
│   ├── fiducial_features.ipnb
│   └── consistency.ipnb
├── results/
│   ├── central_history.csv
│   ├── fedavg_micro_macro_full_history.csv
│   ├── fedprox_round_history.csv
│   └── cfedopt_round_history.csv
├── figures
```

