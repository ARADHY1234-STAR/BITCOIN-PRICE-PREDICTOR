# Bitcoin Price Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting **Bitcoin prices** using **machine learning regression models**.  
The goal is not to perfectly predict the market (which is extremely hard), but to **understand time-series data, feature preparation, and model behavior** on financial datasets.

This project was built as a **learning and experimentation project** to strengthen skills in data analysis and machine learning.

---

## 📊 Dataset
## The dataset is too large to upload to Github.
Download it from : <https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data>
- Features include:
  - Date
  - Open price
  - High price
  - Low price
  - Close price
  - Volume

> ⚠️ Note: Cryptocurrency prices are highly volatile and influenced by many external factors. Predictions from this model should **not** be used for financial decisions.

---

## 🧠 Machine Learning Approach
The following steps were followed:

1. Data loading and preprocessing  
2. Feature selection and scaling  
3. Train-test split  
4. Model training  
5. Model evaluation using regression metrics  

### Models Used
- Support Vector Machine (SVR)
- Linear Regression *(optional / for comparison)*

---

## 📈 Evaluation Metrics
The model performance was evaluated using:
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help understand how well the model fits historical price trends.

---

## 🔍 Key Learnings
- Financial time-series data is noisy and difficult to model
- Feature scaling is critical for models like SVM
- High accuracy does not guarantee real-world reliability
- Machine learning models have limitations in volatile markets

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## 🚀 How to Run the Project
1. Clone the repository
   ```bash
   git clone https://github.com/USERNAMEaradh/bitcoin-price-prediction.git
