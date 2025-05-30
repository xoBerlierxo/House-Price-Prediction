# 🏠 California House Price Prediction Using XGBoost

This project uses the XGBoost regression model to predict housing prices in California based on various features such as median income, house age, population, and proximity to the ocean. The dataset is sourced from Kaggle and is a widely used dataset for regression tasks.

## 📌 Project Overview

- Performed exploratory data analysis and preprocessing (null handling, encoding, feature scaling)
- Used `train_test_split` for creating training and test sets
- Trained multiple regression models and selected **XGBRegressor** based on performance
- Achieved an **R² score of 0.9375** on the test set
- Used visualizations such as histograms, heatmaps, and scatter plots to understand trends

## 🔧 Tech Stack

- **Languages & Libraries:** Python, Pandas, NumPy, scikit-learn, XGBoost, Matplotlib, Seaborn
- **IDE/Tools:** Jupyter Notebook / Google Colab

## 📊 Dataset

The dataset contains California housing data with features such as latitude, longitude, median income, housing age, number of rooms, and more.  
**Link:** [Kaggle – California Housing Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

## 📁 Folder Structure
- House_price_Prediction.ipynb
- california_housing.csv
- requirements.txt

## 🚀 How to Run

1. Clone this repository  
   `git clone https://github.com/your-username/california-price-prediction.git`

2. Install the required libraries  
   `pip install -r requirements.txt`

3. Open `House_price_Prediction.ipynb` in Jupyter or Colab and run the cells

## 📈 Results

- Final model: **XGBRegressor**
- R² Score: **0.9375**
- Evaluation metrics used: R² score, Mean Absolute Error, Mean Squared Error

---

**Note:** This project demonstrates the power of gradient boosting algorithms for real-world regression problems. It is built purely for learning and experimentation purposes.
