# 🚗 Used Car Price Prediction

This project predicts the selling price of used cars using machine learning techniques. The dataset is from Kaggle and contains various features about used cars like year, brand, kilometers driven, fuel type, and more.

## 📊 Dataset

- **Source:** Kaggle *(insert dataset link if public)*
- **Features include:**
  - Car Name
  - Year of Manufacture
  - Present Price
  - Kilometers Driven
  - Fuel Type
  - Seller Type
  - Transmission
  - Owner

## ⚙️ Workflow

1. **Data Cleaning**
   - Removed duplicates and missing values
   - Converted categorical variables to numeric
   - Removed outliers (if any)

2. **Exploratory Data Analysis (EDA)**
   - Visualized price trends by fuel type, year, brand, etc.
   - Checked correlation between features and target

3. **Modeling**
   - Algorithms used:
     - Linear Regression
     - Random Forest Regressor
     - XGBoost Regressor *(if used)*
   - Evaluated using:
     - Mean Absolute Error (MAE)
     - R² Score
     - Root Mean Squared Error (RMSE)

4. **Best Result**
   - Model: *(e.g., Random Forest Regressor)*
   - R² Score: *XX.X%*  
   *(replace with your actual score)*

## 📁 Files

- `Used_car_prediction.ipynb` — Main notebook
- `train.csv`, `test.csv` — Dataset files
- `README.md` — This file

## 📦 Libraries Used

- pandas  
- numpy  
- matplotlib, seaborn  
- scikit-learn  
