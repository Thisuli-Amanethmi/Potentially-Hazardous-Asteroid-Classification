# Potentially Hazardous Asteroid (PHA) Classification with XAI

An Interpretable Ensemble Learning Framework for Planetary Defense

## 🚀 Overview
This repository contains the source code for my Individual Research Project (IRP) at Robert Gordon University. The project focuses on automating the detection of Potentially Hazardous Asteroids (PHAs) using the NASA JPL Small-Body Database.The core contribution of this work is the integration of ADASYN-based resampling with Optimized Stacking Ensembles and Explainable AI (SHAP/LIME) to ensure that machine learning predictions align with the physical laws of orbital mechanics.

## 🧠 Key Features
Temporal Validation: Data split by year (Train: 2000–2017, Test: 2018–2025) to simulate real-world discovery cycles.
Physics-Based Feature Engineering: Custom risk scoring for MOID (Minimum Orbit Intersection Distance) and Absolute Magnitude (H).
Imbalance Handling: Comparative analysis of SMOTE vs. ADASYN for minority class synthesis.
Advanced Ensembling: A multi-stage Stacking Classifier featuring XGBoost, LightGBM, CatBoost, and Extra Trees, tuned via Bayesian Optimization (Optuna).
XAI Audit: Global interpretability with SHAP to validate the 0.05 AU MOID threshold and local interpretability with LIME.

## 📊 Performance Summary - Stacking Ensemble Model
Accuracy: 99.6%
Recall (Sensitivity): 95.1%
F1-Score: 0.968
ROC-AUC: 0.999
