# melbourne-house-price-prediction

````markdown
# 🏡 Melbourne House Price Prediction using Regression

This project applies regression techniques (Linear Regression, Ridge, and Lasso) to identify the most influential features on house prices in Melbourne, Australia. The analysis involves data preprocessing, feature selection, model training, and performance evaluation.

---

## 📌 Project Objective

The objective of this project is to apply regression models to:
- Clean and preprocess a real estate dataset.
- Handle missing values and categorical data.
- Identify the most important factors affecting housing prices.
- Evaluate model performance using R² and training/test accuracy.

---

## 📂 Dataset

- Source: Melbourne Housing Market dataset (`Melbourne_housing_FULL.csv`)
- Rows: 34,857
- Features include:
  - **Suburb, Rooms, Type, Method, SellerG**
  - **Distance to CBD, Regionname, CouncilArea**
  - **Bedroom2, Bathroom, Car, Landsize, BuildingArea, YearBuilt**
  - **Price (Target Variable)**

---

## 📊 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📈 Models Implemented

| Model             | Train Score | Test Score | R² Score |
| ----------------- | ----------- | ---------- | -------- |
| Linear Regression | 0.684       | 0.257      | 0.257    |
| Ridge Regression  | 0.662       | 0.667      | 0.667    |
| Lasso Regression  | 0.678       | 0.674      | 0.674    |

---

---

## ✅ Key Learnings

* Effective handling of missing values.
* One-hot encoding with high-dimensional categorical data.
* Importance of regularization in regression models.
* Comparing model performance with train/test splits.

---


### 📄 `requirements.txt`

```txt
numpy
pandas
matplotlib
seaborn
scikit-learn
````
