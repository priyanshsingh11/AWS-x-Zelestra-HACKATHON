# 🚀 Zelestra X AWS ML Ascend Challenge - 2nd Edition

This repository contains my solution for the **Zelestra X AWS ML Ascend Challenge - 2nd Edition**.

The project focuses on building a **machine learning model** to predict the efficiency of a system based on various features using **Python, pandas, scikit-learn, XGBoost, and TensorFlow/Keras**.

---

## 📂 Project Structure


---

## 🔄 Workflow

- **Data Loading**
  - Reads training and test datasets using `pandas`.

- **Data Preprocessing**
  - Drops unnecessary columns.
  - Converts data types and handles missing values.
  - Scales features using `MinMaxScaler`.

- **Feature Engineering**
  - Separates features (`X`) and target variable (`y`).

- **Model Training**
  - Splits data into training and validation sets.
  - Trains an **XGBoost regressor**.

- **Model Evaluation**
  - Calculates a **custom score based on RMSE**.

- **Prediction & Submission**
  - Generates predictions for the test set.
  - Prepares the `submission.csv` file for final submission.

---

## 📦 Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- xgboost
- tensorflow

> 💻 **Install all dependencies:**

```bash
pip install -r requirements.txt
