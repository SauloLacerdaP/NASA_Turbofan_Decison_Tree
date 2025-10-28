# 🛠️ Decision Trees on NASA Turbofan (FD001) - Remaining Useful Life Prediction 

## 📘 Project Overview
This project was developed as part of an academic exercise on **machine learning and predictive maintenance**.  
The goal was to analyze the **NASA Turbofan FD001 dataset (C-MAPSS)** and apply **Decision Tree models** to predict whether an engine is approaching failure, based on sensor readings collected over time.

The workflow covers all main stages of a predictive modeling project — from data preprocessing and feature extraction to model training, evaluation, and interpretation of decision rules.

All code is implemented in **Python** across two Jupyter notebooks:
- `NASA_prep.ipynb` → data cleaning, RUL computation, feature engineering  
- `Decision_tree_models.ipynb` → model training, evaluation, and visualization

---

## 🎯 Objectives
- Compute the **Remaining Useful Life (RUL)** for each engine in the NASA FD001 dataset.  
- Convert the regression task into a **binary classification problem**:
  - `fail_soon = 1` → engine will fail within the next 30 cycles.  
  - `fail_soon = 0` → engine is operating safely.  
- Extract **statistical and trend-based features** using sliding windows.  
- Train and evaluate **ID3-like** and **J48-like** Decision Tree models using `scikit-learn`.  
- Interpret the resulting trees to understand which sensors contribute most to predicting failures.

---

## 🧰 Libraries Used

- **Python 3.10**  
- **pandas** 
- **NumPy**
- **scikit-learn**
- **Matplotlib** 
 
