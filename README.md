# PRODIGY_DS_01


# 🏠 House Price Prediction using Linear Regression

This project implements a **Linear Regression** model to predict house prices based on key features such as **square footage**, **number of bedrooms**, and **number of bathrooms**. It utilizes the dataset provided in the [Kaggle: House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data) competition.

---

## 📁 Dataset
- **Source**: [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
- **File used**: `train.csv`

---

## 🧠 Features Used
| Feature         | Description                                 |
|-----------------|---------------------------------------------|
| `GrLivArea`     | Above ground living area in square feet     |
| `BedroomAbvGr`  | Number of bedrooms above ground             |
| `FullBath`      | Number of full bathrooms                    |
| `HalfBath`      | Number of half bathrooms                    |
| `SalePrice`     | Target variable (house price)               |

> Note: `TotalBath` is created as `FullBath + 0.5 * HalfBath` to represent total bathroom value.

---

## 🚀 Getting Started

### 🔧 Requirements
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

Install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
