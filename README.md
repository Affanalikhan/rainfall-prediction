<div align="center">

# 🌧️ Rainfall Prediction using Machine Learning

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org)
[![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org)

> Binary classification model to predict whether it will rain tomorrow based on meteorological data.

</div>

---

## 🎯 Overview

This project builds a classification model to predict next-day rainfall using weather observations. It tackles a real-world imbalanced classification problem with meteorological features like temperature, humidity, wind speed, and pressure.

---

## 🔍 What's Inside

- **EDA** — Weather pattern analysis, seasonal trends, feature correlations
- **Preprocessing** — Missing value imputation, feature scaling, class imbalance handling (SMOTE / class weights)
- **Models** — Logistic Regression, Random Forest, XGBoost, SVM
- **Evaluation** — Accuracy, Precision, Recall, F1-score, ROC-AUC curve

---

## 📊 Key Features

| Feature | Description |
|---|---|
| Temperature (Min/Max) | Daily temperature range |
| Humidity | Morning and afternoon humidity % |
| Wind Speed & Direction | Wind gust and direction |
| Pressure | Atmospheric pressure readings |
| Cloud Cover | Cloud amount at 9am and 3pm |
| RainToday | Whether it rained today (binary) |

---

## 🚀 Getting Started

```bash
git clone https://github.com/Affanalikhan/rainfall-prediction.git
cd rainfall-prediction
pip install pandas numpy matplotlib seaborn scikit-learn xgboost imbalanced-learn jupyter
jupyter notebook
```

---

## 🛠️ Tech Stack

`Python` · `Pandas` · `NumPy` · `Scikit-learn` · `XGBoost` · `Matplotlib` · `Seaborn` · `Jupyter`

---

<div align="center">
Made with ❤️ by <a href="https://github.com/Affanalikhan">Affan Ali Khan</a>
</div>
