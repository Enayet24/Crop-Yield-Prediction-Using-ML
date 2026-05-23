# 🌾 Crop Yield Prediction Using Machine Learning

## 📘 Overview

This project focuses on predicting **crop yield using machine learning techniques** based on climatic, agricultural, and temporal factors. The study is designed around real-world agricultural data from Bangladesh and aims to analyze how environmental and input variables influence crop productivity.

Multiple supervised learning models were implemented and compared to identify the most effective approach for accurate yield prediction. The project follows a complete **data science pipeline**, including preprocessing, exploratory data analysis, feature engineering, dimensionality reduction, model training, and evaluation.

---

## 🎯 Objectives

The main objectives of this project are:

- To analyze agricultural and climatic factors affecting crop yield  
- To build predictive models for crop yield estimation  
- To compare multiple machine learning algorithms  
- To apply feature engineering and dimensionality reduction techniques  
- To evaluate model performance using robust statistical metrics  

---

## 🌍 Dataset Description

- **Source:** [Kaggle](https://www.kaggle.com/datasets/patelris/crop-yield-prediction-dataset) 
- **Scope:** Filtered for **Bangladesh-specific agricultural data**  

### Key Features:
- Year  
- Rainfall (mm/year)  
- Temperature (°C)  
- Pesticides (tonnes)  
- Crop Type (categorical)  

The dataset spans multiple years and includes environmental and agricultural inputs relevant to crop production.

---

## 🧹 Methodology

- 📥 Data Collection
- ⚙️ Data Preprocessing
- 📊 Exploratory Data Analysis (EDA)
- 🧪 Feature Engineering
- 📉 Dimensionality Reduction
---

### 🤖 Model Development

The dataset was split into **80% training and 20% testing**.

Models implemented:

- 🌳 Random Forest Regressor  
- ⚡ AdaBoost Regressor  
- 📍 K-Nearest Neighbors (KNN) Regressor  
- 📈 Support Vector Machine (SVM) Regressor  

Hyperparameter tuning was applied to optimize performance.

---

### 📏 Model Evaluation

Models were evaluated using:

- RMSE (Root Mean Squared Error)  
- R² Score  

Additional analysis included:

- Actual vs Predicted plots  
- Residual analysis  
- Feature importance (Random Forest)  

---

### 🔁 Model Validation

To ensure robustness:

- 5-Fold Cross Validation was applied (best model: Random Forest)  
- Learning curves were used to analyze overfitting/underfitting behavior  

---

## 📊 Results Summary

- Random Forest achieved the best overall performance  
- Ensemble models outperformed individual learners  
- Feature engineering significantly improved model performance  

---

## 🛠️ Tech Stack

- Python 🐍  
- Pandas & NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  

---

## 📂 Contribution
- [Enayet Ali](https://github.com/Enayet24)
- [Iffat Islam Aria](https://github.com/iffat-islam-aria)
- [Md Mamun Molla](https://github.com/mamun007molla)
- [Rida Nawar](https://github.com/ridanawar-1081)
