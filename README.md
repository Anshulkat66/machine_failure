# 🔧 Machine Failure Prediction System

A Machine Learning based Predictive Maintenance Project to detect industrial machine failures before breakdowns happen 🚀

📌 Overview

This project focuses on predicting different types of machine failures using industrial sensor data and machine learning techniques. The main objective is to reduce unexpected downtime, improve maintenance planning, and increase overall machine reliability.

The system analyzes machine operating conditions such as temperature, rotational speed, torque, and tool wear to identify potential failures in advance. Multiple ML models were trained and compared to achieve better prediction accuracy.

# ⚙️ Failure Types Predicted

The model predicts the following machine failure categories:

🛠️ Tool Wear Failure (TWF)

🌡️ Heat Dissipation Failure (HDF)

⚡ Power Failure (PWF)

📈 Overstrain Failure (OSF)

🎲 Random Failure (RNF)

# 🚀 Features

✅ Complete data preprocessing pipeline

✅ Feature engineering for better predictions

✅ Multi-label classification approach

✅ Handling of imbalanced failure classes

✅ Comparison of multiple ML models

✅ Cross-validation based evaluation

✅ Saved trained pipelines for future deployment

# 📊 Dataset & Analysis

The project uses industrial machine sensor data containing:

Air Temperature

Process Temperature

Rotational Speed

Torque

Tool Wear

Detailed exploratory data analysis (EDA) was performed to understand feature distributions, correlations, and failure patterns.

# 🧠 Feature Engineering

Additional features were created to improve model performance, including:

🌡️ Temperature Difference = Process Temp − Air Temp

⚙️ Power Proxy = Rotational Speed × Torque

These engineered features helped the models better capture machine behavior and operating conditions.

# 🔄 Machine Learning Workflow

📍 Data Preprocessing

-Missing value handling

-Feature scaling using StandardScaler

-Encoding categorical features using OneHotEncoder

-Combined preprocessing using ColumnTransformer

📍 Model Training

Implemented and compared multiple machine learning models:

 -Logistic Regression

 -Random Forest Classifier

 -XGBoost Classifier

 -LightGBM Classifier

📍 Multi-Label Classification

Used the One-vs-Rest strategy to train separate classifiers for each machine failure type.

📍 Model Evaluation

Models were evaluated using:

📈 F1-Score

🔍 Cross Validation

⚖️ Imbalanced Class Handling
