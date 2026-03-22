# Bike-Sharing-Demand-Prediction
End-to-end machine learning project for predicting bike rental demand using regression models, feature engineering, and hyperparameter tuning with Random Forest, Gradient Boosting, and XGBoost.
## Project Overview
This project focuses on building a robust machine learning pipeline to predict bike rental demand based on historical usage data and environmental factors. The solution leverages advanced regression techniques, feature engineering, and hyperparameter optimization to achieve high predictive performance.

---

## Objective
To accurately predict the count of total bike rentals (`cnt`) using various independent variables such as weather conditions, time-based features, and seasonal trends.

---

## Dataset Description
The dataset includes:
- Temporal features: year, month, weekday, hour
- Weather features: temperature, humidity, windspeed
- Seasonal indicators: season, holiday, working day
- Target variable: `cnt` (total bike rentals)

---

## Technical Approach

### 1. Exploratory Data Analysis (EDA)
- Distribution analysis of numerical features
- Categorical feature impact on demand
- Time-series trend analysis (hourly, daily, seasonal)
- Correlation heatmap to identify multicollinearity

---

### 2. Data Preprocessing
- Handling missing/null values
- Encoding categorical variables (Label/One-Hot Encoding)
- Feature scaling using StandardScaler/MinMaxScaler
- Outlier detection and treatment

---

### 3. Feature Engineering
- Extraction of time-based patterns (hour, weekday, seasonality)
- Creation of interaction features
- Removal of redundant and highly correlated features

---

### 4. Model Building
Implemented multiple regression models:

- Linear Regression (baseline)
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

---

### 5. Hyperparameter Tuning
- GridSearchCV / RandomizedSearchCV used for optimization
- Cross-validation to ensure model generalization
- Parameter tuning for:
  - Number of estimators
  - Max depth
  - Learning rate
  - Subsampling

---

### 6. Model Evaluation
Models were evaluated using:
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

---

## Final Model Selection
The best model was selected based on:
- Highest R² score
- Lowest RMSE
- Stability across cross-validation folds

---

## Key Insights
- Demand peaks during working hours and weekends
- Weather conditions significantly influence bike usage
- Seasonal trends strongly affect rental patterns
- Temperature has a positive correlation with demand

---

## Tech Stack
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Google Colab

---

## Project Structure

Bike-Sharing-Demand-Prediction/
│── Bike_Sharing.ipynb
│── README.md


---

## How to Run
1. Open the notebook in Google Colab
2. Upload the dataset
3. Execute all cells sequentially

---

## Conclusion
The project demonstrates a complete machine learning workflow from data preprocessing to model deployment-ready predictions, highlighting the effectiveness of ensemble methods in regression problems.

---

## Author
**Prishita Matreja**
