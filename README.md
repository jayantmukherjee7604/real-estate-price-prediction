# 🏠 Real Estate Price Prediction

A machine learning project to predict house prices based on features like distance to MRT station, number of convenience stores, location (latitude & longitude), and house age using regression techniques.

---

## 🌳 Project Structure
🏠 Real Estate Price Prediction
│
├── 📌 Problem Statement
│ → Predict house prices based on features like:
│ • Distance to MRT station
│ • Number of convenience stores
│ • Latitude, Longitude
│ • House age
│
├── 📂 Dataset (Real_Estate.csv)
│ → Features: House age, MRT distance, Stores, Latitude, Longitude
│ → Target: House price of unit area
│
├── 🔍 Exploratory Data Analysis (EDA)
│ → .describe() for summary stats
│ → Histograms → distribution check
│ → Scatter plots → relationship with target
│ → Correlation Matrix → quantify feature-target relationships
│
├── 🧠 Feature Engineering
│ → Binned house age into: New / Mid-Age / Old
│ → Binned MRT distance into: Very Close / Close / Far / Very Far
│ → One-hot encoded the new categorical features
│
├── 🤖 Model Building
│ → Models used:
│ • Linear Regression ✅ (Best performer)
│ • Random Forest Regressor
│ • XGBoost Regressor
│ → Train-test split (80-20)
│ → Performance metrics:
│ • R² Score
│ • RMSE
│ • MAE
│
├── 📈 Model Evaluation
│ → Actual vs Predicted scatter plot
│ → Interpretation of coefficients
│ → Feature importance discussed
│
├── 🧪 Results Summary
│ → Linear Regression performed best (R² ≈ 0.55)
│ → Most impactful features:
│ • MRT Distance (Negative)
│ • Convenience Stores (Positive)
│ • Latitude/Longitude (Geographic influence)
│
└── 🚀 Future Improvements
→ Feature engineering (interactions, transformations)
→ More data & external features (e.g., crime rate, school distance)
→ Hyperparameter tuning for complex models

