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

# Repository Structure

ECG-FL-XAI/
│
├── README.md
├── requirements.txt
├── LICENSE
│
├── data/
│   ├── class_mapping.csv
│   ├── client_statistics.csv
│   └── sample_data/
│
├── preprocessing/
│   ├── preprocessing.py
│   ├── label_harmonization.py
│   ├── feature_extraction.py
│
├── models/
│   ├── resnet34_1d.py
│   ├── fedavg.py
│   ├── fedprox.py
│   └── fedadam.py
│
├── training/
│   ├── train_fedavg.py
│   ├── train_fedprox.py
│   ├── train_fedadam.py
│
├── explainability/
│   ├── gradcam.py
│   ├── shap_analysis.py
│
├── uncertainty/
│   ├── mc_dropout.py
│
├── analysis/
│   ├── consistency_analysis.py
│   ├── correlation_analysis.py
│
├── results/
│   ├── classification_results.csv
│   ├── consistency_scores.csv
│   ├── uncertainty_scores.csv
│   └── correlation_results.csv
│
├── figures/
│   ├── architecture.png
│   ├── gradcam_examples/
│   ├── shap_examples/
│   ├── correlation_plots/
│
└── notebooks/
    ├── preprocessing.ipynb
    ├── training.ipynb
    ├── gradcam.ipynb
    ├── shap.ipynb
    └── analysis.ipynb

