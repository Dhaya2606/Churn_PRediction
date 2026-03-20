# 🚀 Customer Churn Prediction API

## 📌 Project Overview

This project focuses on building a **Machine Learning model to predict customer churn** based on features like age, monthly spend, tenure, and plan type.

The goal is to create a pipeline from **data preprocessing → model training → API deployment** for real-time predictions.

---

## 🎯 Work Done

### 🔹 Data Preprocessing

* Handled missing values
* Encoded categorical feature (`plan_type`)
* Converted target variable (`churn`) into numerical format

### 🔹 Feature Engineering

* Selected relevant features:

  * Age
  * Monthly Spend
  * Tenure
  * Plan Type
* Applied **StandardScaler** for feature scaling

### 🔹 Model Building

* Used **Random Forest Classifier**
* Split data into training and testing sets
* Trained the model on processed data

### 🔹 Hyperparameter Tuning

* Used **GridSearchCV** to find optimal parameters
* Improved model performance

### 🔹 Model Evaluation

* Evaluated using:

  * Accuracy
  * Confusion Matrix
  * Classification Report

### 🔹 Model Saving

* Saved trained model using `pickle`
* Saved scaler for consistent preprocessing during prediction

---

## 🌐 API Development

* Built a REST API using **FastAPI**
* Created endpoint:

  * `POST /predict`
* API takes user input and returns churn prediction (`yes` / `no`)

---

## ⚠️ Note on API Execution

* The API was developed successfully using FastAPI
* However, running the API directly inside **Jupyter Notebook caused issues**, since FastAPI requires a `.py` file and terminal execution
* The API runs correctly when executed from a **VS Code terminal or command line using Uvicorn**

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* FastAPI
* Uvicorn

---

## 🚀 Status

* ✅ Model built and evaluated
* ✅ API created
* ⚠️ Deployment setup in progress (tested locally)

---

## 👨‍💻 Author

Dhaya Kumar
