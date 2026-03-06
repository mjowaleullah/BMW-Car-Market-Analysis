# 🚗 BMW Car Market Analysis

> Predicting BMW used car prices using Machine Learning

## 📌 Overview
This project analyzes the **BMW Used Car Market** dataset containing 10,664 records to build a price prediction model. Multiple ML models were trained and compared, with **XGBoost achieving 95.54% accuracy (R²)**.

## 📊 Dataset
- **Source:** [Kaggle — BMW Car Market Insights](https://www.kaggle.com/datasets/guriya79/bmw-cars)
- **Records:** 10,664 cars (after removing duplicates)
- **Features:** `model`, `year`, `transmission`, `mileage`, `fuelType`, `tax`, `mpg`, `engineSize`
- **Target:** `price` (£)

## 🤖 Models Compared

| Model | R² Score | RMSE |
|---|---|---|
| Linear Regression | 74.63% | £5,622 |
| Random Forest | 94.74% | £2,559 |
| **XGBoost** ✅ | **95.54%** | **£2,356** |

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189AB4?style=for-the-badge)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)

## 🚀 How to Run
```bash
git clone https://github.com/mjowaleullah/BMW-Car-Market-Analysis.git
cd BMW-Car-Market-Analysis
pip install -r requirements.txt
jupyter notebook bmw.ipynb
```

## 📁 Project Structure
```
BMW-Car-Market-Analysis/
│
├── bmw.csv              # Dataset
├── bmw.ipynb            # Main notebook
├── requirements.txt     # Dependencies
└── README.md
```

## 📈 Key Findings
- **Year** and **Engine Size** are the most important features for price prediction
- XGBoost outperforms all other models with **95.54% R²** and **£2,356 RMSE**
- Diesel cars dominate the dataset (65% of records)

## 📦 Requirements
```
pandas
numpy
scikit-learn
xgboost
matplotlib
seaborn
ydata-profiling
```
