# CO₂ Emission Prediction by Vehicles

A machine learning project that predicts vehicle CO₂ emissions (g/km) from engine, fuel and vehicle features, comparing three regression models.

Completed during my Data Analytics training and internship at Techolas Technologies.

## Objective
Predict CO₂ emissions (g/km) of vehicles. This is a regression problem.

## Dataset
- Source: Kaggle (CO2 Emissions Canada)
- 7,385 rows and 12 columns
- Features include make, model, vehicle class, engine size, cylinders, transmission, fuel type and fuel consumption

## Tools & Technologies
- **Python** (Pandas, NumPy)
- **Scikit-learn** (LinearRegression, RandomForestRegressor, DecisionTreeRegressor, StandardScaler, LabelEncoder)
- **Matplotlib, Seaborn**
- **Jupyter Notebook**

## Project Workflow
1. **Data inspection:** Checked shape, data types, missing values and summary statistics
2. **Data preparation:** Cleaned column names and applied Label Encoding to categorical columns
3. **Exploratory analysis:** Vehicle class distribution, correlation heatmap, CO₂ distribution, CO₂ by fuel type, engine size vs CO₂
4. **Modelling:** 80/20 train-test split; trained Linear Regression (with scaling), Random Forest Regressor and Decision Tree Regressor
5. **Evaluation:** Compared models using R², MSE and MAE

## Model Results (test set)

| Model | R² Score |
|-------|----------|
| Linear Regression | 0.9125612688263743 |
| Random Forest Regressor | 0.9994249727335394 |
| Decision Tree Regressor | 0.996314399324622 |

## Files
- `CO2_EMISSION_BY_VEHICLES.ipynb`: Full analysis and models

## Author
**Muhammed Adhil** | [LinkedIn](https://www.linkedin.com/in/adhil-poonakkattayil) | adhilpoonakkattayil@gmail.com
