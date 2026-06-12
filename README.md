# 🏡 House Price Prediction | Kaggle ML Pipeline

This project is an end-to-end Machine Learning pipeline built for the Kaggle **House Prices – Advanced Regression Techniques** competition.

The objective is to predict house sale prices using structured tabular data and apply practical ML concepts from preprocessing to model ensembling.

## 📌 Project Overview

This project covers the complete ML workflow:

* Exploratory Data Analysis (EDA)
* Missing Value Handling
* Skewness-Based Imputation (Mean / Median)
* Outlier Detection and Analysis
* Feature Engineering
* Categorical Encoding
* Model Training and Evaluation
* Ensemble Learning
* Kaggle Submission

---

## 📂 Dataset

Competition:
**House Prices – Advanced Regression Techniques (Kaggle)**

Dataset contains:

* 1460 training samples
* 80 input features
* Target: `SalePrice`

---

## ⚙️ Workflow

### 1. Exploratory Data Analysis

* Distribution analysis
* Correlation analysis
* Feature relationship visualization
* Target variable inspection

### 2. Data Cleaning

* Removed columns with excessive missing values
* Numerical NaN handling using:

  * Mean (approximately symmetric distribution)
  * Median (high skewness)
* Categorical NaN handling using mode / category replacement

### 3. Outlier Handling

* IQR-based detection
* Visual validation before removal

### 4. Feature Engineering

Examples:

* TotalSF
* HouseAge
* Encoded categorical variables

### 5. Modeling

Models explored:

* LightGBM
* XGBoost
* CatBoost
* Voting Regressor Ensemble

### 6. Evaluation

Metric:

* RMSE (Root Mean Squared Error)

---

## 📈 Results

Initial baseline:

* RMSE ≈ 0.13

Kaggle Submission:

* Public leaderboard submission completed

Future Improvements:

* Hyperparameter tuning
* Stacking ensemble
* Cross-validation optimization

---

## 🛠 Tech Stack

Python
Pandas
NumPy
Scikit-learn
LightGBM
XGBoost
CatBoost
Matplotlib
Seaborn

---

## 📬 Author

Kiran Kumar Pradhan

Learning ML by building and experimenting with real-world projects.
