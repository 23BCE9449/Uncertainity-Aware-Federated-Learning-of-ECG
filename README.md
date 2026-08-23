# Uncertainity-Aware-Federated-Learning-of-ECG
#Project Title
Uncertainty-Aware Explainable Federated Learning for Multi-Label ECG Classification

#Overview
This project presents a privacy-preserving framework for multi-label ECG classification using Federated Learning, Explainable Artificial Intelligence (XAI), and Uncertainty Quantification. The framework investigates whether predictive uncertainty can serve as an indicator of explanation consistency across multiple healthcare institutions.

#Key Features
Multi-client Federated Learning
PhysioNet Challenge 2021 ECG Dataset
1D ResNet-34 Architecture
FedAvg, FedProx, and FedAdam
Grad-CAM Explainability
SHAP Feature Attribution
Monte Carlo Dropout Uncertainty Estimation
Cross-Client Explanation Consistency Analysis
Correlation Analysis Between Uncertainty and Explainability

#Dataset
PhysioNet Challenge 2021
Federated Clients:
Chapman-Shaoxing
CPSC-2018
Georgia
Ningbo
PTB-XL

#Final Taxonomy:
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


#Methodology
Raw ECG
    ↓
Preprocessing
    ↓
Label Harmonization
    ↓
Federated Learning
    ↓
1D ResNet-34
    ↓
FedAvg / FedProx / FedAdam
    ↓
Grad-CAM + SHAP
    ↓
Monte Carlo Dropout
    ↓
Consistency Analysis
    ↓
Correlation Analysis

