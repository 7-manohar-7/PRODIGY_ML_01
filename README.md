# 🏠 PRODIGY_ML_01 – House Price Prediction

This project aims to predict house prices using a Linear Regression model. The model is trained on a dataset containing various features such as area, number of rooms, and location.

---

## 📌 Project Description

Accurate house price prediction is vital for real estate planning and investment. This model uses historical housing data to estimate the selling price of a house based on key attributes.

---

## 🛠 Tech Stack / Tools Used

- **Language**: Python
- **IDE**: Jupyter Notebook
- **Libraries**:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - Scikit-learn
- **Dataset**: House Prices Dataset (from Kaggle)

---

## 🧠 Problem Statement

Given a dataset of houses with features such as area, number of bedrooms, location, etc., build a regression model that can predict the price of a house accurately.

---

## 🧪 Solution Approach

1. **Data Collection**: Imported the dataset from Kaggle.
2. **Data Preprocessing**:
   - Handled missing values
   - Encoded categorical variables
   - Normalized numerical features
3. **Model Building**:
   - Used Linear Regression from Scikit-learn
   - Trained and validated on train-test split
4. **Evaluation**:
   - Metrics: Mean Squared Error (MSE), R² Score
   - Visualization of actual vs predicted prices

---

## 💻 Installation & Setup

```bash
git clone https://github.com/yourusername/house-price-prediction.git
cd house-price-prediction
pip install -r requirements.txt
jupyter notebook
