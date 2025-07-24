### House-Price-Prediction-using-Linear-Regression

This project applies **Linear Regression** to predict house prices using the **California Housing dataset** provided by `sklearn.datasets`.

## 📌 Project Overview

- **Goal**: Predict median house value (in $100,000s) based on various features like income, location, etc.
- **Dataset**: California Housing dataset (in-built with sklearn)
- **Algorithm**: Linear Regression
- **Libraries**: scikit-learn, pandas, matplotlib

## 📊 Features Used

- MedInc: Median Income in block
- HouseAge: Median house age
- AveRooms: Average rooms per household
- AveBedrms: Average bedrooms
- Population: Block population
- AveOccup: Average occupancy
- Latitude, Longitude

## 🔁 Workflow

1. Loaded dataset using `fetch_california_housing()`
2. Converted it to Pandas DataFrame
3. Split into train/test sets
4. Applied Linear Regression
5. Evaluated model using:
   - Mean Squared Error (MSE)
   - R² Score
6. Visualized:
   - Actual vs Predicted

## ✅ Results

- 📉 **MSE**:0.5371887472544282
- 📈 **R² Score**:0.608042867012949

The model shows decent predictive performance for a basic regression algorithm.

## 🧠 Skills Practiced

- Model training and testing
- Regression interpretation
- Evaluation metrics
- Data visualization
