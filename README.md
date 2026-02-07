# CAR-MODEL-IN-ML
A linear regression model to predict car prices.
🚗 Car Price Prediction Using Machine Learning (Regression)
📌 Project Overview

This project applies machine learning regression models to predict car prices in Million ₦ based on vehicle features.
The goal is to build a beginner-friendly end-to-end pipeline including data cleaning, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

Because the target variable (Amount) is numeric, this is a regression problem, not classification.

📊 Dataset Features

The dataset contains the following attributes:

Location

Maker (Brand)

Year

Colour

Type (Brand New / Used, etc.)

Distance_Km

Amount (Million ₦) — Target Variable

⚙️ Project Workflow

The notebook follows these main steps:

Import required libraries

Load dataset from Google Drive

Data understanding and inspection

Data cleaning

Remove irrelevant columns

Handle duplicates

Fix structural errors

Fill missing values

Exploratory Data Analysis (EDA)

Feature Encoding and Scaling

Train–Test Split

Model Training:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Model Evaluation using:

MAE

RMSE

R² Score

Predicting price for a new car

🤖 Models Used

Linear Regression

Decision Tree

Random Forest

Gradient Boosting

Gradient Boosting achieved the best overall performance in this project.

📈 Technologies & Libraries

Python

Pandas

NumPy

Matplotlib & Seaborn

Scikit-learn

Google Colab

🎯 Project Goal

To demonstrate how machine learning can be used to estimate vehicle prices based on real-world car attributes.

▶️ How to Run

Open the notebook in Google Colab

Mount Google Drive

Upload the dataset (Car.xlsx)

Run all cells sequentially
