# 🚗 Car Price Prediction Using Machine Learning (Regression)

## 📌 Project Overview
This project uses **machine learning regression models** to predict car prices in **Million ₦** based on vehicle characteristics.  
It demonstrates a beginner-friendly end-to-end workflow including data cleaning, exploratory data analysis (EDA), feature engineering, model training, evaluation, and prediction.

Since the target variable (**Amount**) is numeric, this is a **Regression Problem**.

---

## 📊 Dataset Features
The dataset contains the following variables:

- **Location** – City where the car is listed
- **Maker** – Car brand
- **Year** – Manufacturing year
- **Colour** – Vehicle colour
- **Type** – Car condition/type
- **Distance_Km** – Distance driven
- **Amount (Million ₦)** – Target variable (car price)

---

## ⚙️ Project Workflow
The notebook follows these main steps:

1. Import required libraries
2. Load dataset from Google Drive
3. Data Understanding (`info`, `describe`)
4. Data Cleaning
   - Remove irrelevant columns
   - Remove duplicates
   - Fix structural errors
   - Handle missing values
5. Exploratory Data Analysis (EDA)
6. Feature Encoding (Label Encoding)
7. Feature Scaling (StandardScaler)
8. Train-Test Split
9. Model Training
10. Model Evaluation
11. Price Prediction for a New Car

---

## 🤖 Machine Learning Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor

📌 **Best Performing Model:** Gradient Boosting Regressor

---

## 📈 Evaluation Metrics
Models were evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

---

## 🛠️ Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

---

## ▶️ How to Run the Project
1. Open the notebook in **Google Colab**
2. Mount your Google Drive:
   ```python
   from google.colab import drive
   drive.mount('/content/drive')
