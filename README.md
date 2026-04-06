# 📊 Retail Promotion Efficiency Analysis

![Python](https://img.shields.io/badge/Python-3.9-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)
![XGBoost](https://img.shields.io/badge/XGBoost-Model-green)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-lightgrey)

---

## 🚀 Overview
This project builds a machine learning framework to estimate baseline (non-promotional) sales and measure the true impact of promotions in retail data.

---

## ❗ Problem
Retailers often overestimate promotion success due to inaccurate baseline calculations, leading to incorrect business decisions and misleading ROI evaluation.

---

## 🧠 Approach
- Cleaned and prepared time-series retail data  
- Performed exploratory data analysis (EDA) to identify trends and seasonality  
- Engineered features such as lag variables, rolling averages, and calendar features  
- Implemented leakage-free modelling using time-based validation  
- Built and compared models:
  - Linear Regression  
  - XGBoost  

---

## ⚙️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- Matplotlib, Seaborn  

---

## 📈 Results
- XGBoost achieved **R² = 0.83** and **RMSE = 27.9**  
- Linear regression provided interpretable baseline but lower accuracy  
- Promotion detection achieved ~80% precision and recall  

---

## 💡 Key Insights
- Promotions create short-term spikes followed by post-promotion dips  
- Simple baseline methods significantly overestimate promotion impact  
- Accurate baseline estimation is critical for reliable ROI measurement  

---

## 🔒 Dataset
The dataset used in this project is confidential (real retail data).  
To maintain privacy, raw data is not shared.  
A similar structure can be recreated using synthetic data.

---

## 🔮 Future Improvements
- Add SHAP for model interpretability  
- Incorporate external factors (holidays, weather)  
- Deploy as a dashboard for business use  
