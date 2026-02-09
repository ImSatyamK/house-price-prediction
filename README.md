# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview
This project predicts **house prices** using **Linear Regression** based on housing and socio-economic features.
The model is trained on the **Boston Housing dataset**, downloaded from **Kaggle**, and implemented using **scikit-learn**.

The goal is to estimate the **median value of owner-occupied homes** based on input features.

---

## 📊 Dataset Information
- **Dataset Name:** Boston Housing Dataset
- **Source:** Kaggle
- **Total Records:** 506
- **Features:** 13 numerical variables
- **Target Variable:** `MEDV` (Median house value)

### Important Features:
- CRIM – Per capita crime rate
- ZN – Residential land zoned
- INDUS – Non-retail business acres
- NOX – Nitric oxide concentration
- RM – Average number of rooms per dwelling
- AGE – Proportion of old houses
- DIS – Distance to employment centers
- TAX – Property tax rate
- PTRATIO – Pupil-teacher ratio
- LSTAT – Percentage of lower-status population

---

## 🧠 Problem Type
This is a **supervised regression problem**:
- Input → numerical features
- Output → continuous value (house price)

---

## ⚙️ Technologies Used
- Python 3
- scikit-learn
- NumPy
- Pandas
- Matplotlib
- Seaborn

---

## 📦 Installation
Install required dependencies:
```bash
pip install scikit-learn numpy pandas matplotlib seaborn
```

---

## 📁 Project Structure
```text
house-price-prediction/
│
├── data/
│   └── boston_housing.csv
│
├── house_price_prediction.py
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run the Project
1. Clone the repository:
```bash
git clone https://github.com/your-username/house-price-prediction.git
```

2. Navigate to the project directory:
```bash
cd house-price-prediction
```

3. Run the Python script:
```bash
python house_price_prediction.py
```

---

## 🧪 Machine Learning Workflow
1. Load dataset from CSV
2. Perform basic data exploration
3. Split data into training and testing sets
4. Apply feature scaling
5. Train Linear Regression model
6. Evaluate model performance
7. Predict house prices

---

## 📈 Model Used
### Linear Regression
- Assumes linear relationship between features and target
- Simple and interpretable regression model
- Implemented using `sklearn.linear_model.LinearRegression`

---

## 📊 Model Evaluation
Evaluation metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## ❗ Notes
- Feature scaling improves performance
- Dataset may contain multicollinearity
- Linear Regression is sensitive to outliers

---

## 📚 Learning Outcomes
- Regression problem formulation
- End-to-end ML pipeline
- Feature scaling and evaluation
- Practical use of Linear Regression

---

## 📜 License
This project is intended for **educational purposes only**.