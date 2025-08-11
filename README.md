# 🏢 Building Energy Usage Prediction

## 📌 Project Overview
This project predicts **building energy consumption** using various machine learning regression models.  
The dataset contains features such as **temperature, humidity, occupancy, and equipment usage** that influence total energy usage.  

The goal is to analyze different algorithms and identify the best-performing model for energy efficiency optimization in smart buildings.

---

## 🗂 Dataset
**Source:** [Kaggle - Building Energy Usage Dataset](https://www.kaggle.com)  

**Key Features:**
- Temperature (°C)
- Humidity (%)
- Occupancy (number of people)
- Lighting Usage (kWh)
- Equipment Usage (kWh)
- Energy Usage (Target Variable)

---

## ⚙️ Models Implemented
1. **Linear Regression**
2. **Decision Tree Regressor**
3. **KNN Regressor**
4. **Random Forest Regressor**

---

## 📊 Performance Summary

| Model                | Train RMSE | Test RMSE | Train R²  | Test R²   |
|----------------------|------------|-----------|-----------|-----------|
| Linear Regression    | ~120.65    | ~139.49   | 0.136     | -0.167    |
| Decision Tree        | ~0.00      | ~141.91   | 1.0       | -0.207    |
| KNN Regressor        | ~0.00      | ~141.91   | 1.0       | -0.207    |
| Random Forest        | TBD        | TBD       | TBD       | TBD       |

**Observation:** Decision Tree and KNN models overfit (perfect train score but poor test performance).  
Random Forest is expected to reduce overfitting by averaging multiple decision trees.

---

## 📈 Visualizations
- Scatter Plots: Actual vs. Predicted energy usage
- Line Graphs: Predicted vs. Actual trends
- RMSE & R² comparison charts

---

## 🔮 Future Work
- Implement **XGBoost, Gradient Boosting**
- Perform **feature engineering** for better insights
- Apply **hyperparameter tuning**
- Explore **deep learning models** (LSTM, ANN) for time-series prediction

---

## 📚 References
1. Breiman, L. (2001). *Random Forests*. Machine Learning, 45(1), 5–32.
2. Pedregosa, F., et al. (2011). *Scikit-learn: Machine Learning in Python*. JMLR, 12, 2825–2830.
3. Kaggle. (n.d.). *Building Energy Usage Dataset*.

---
