
---

# Data Science Projects: Kaggle Competitions

Welcome to my Data Science repository! This repository contains my solutions and analyses for Kaggle competitions, specifically focusing on the **Flights Dataset** and **House Pricing Dataset**. The projects include exploratory data analysis (EDA), feature engineering, and machine learning model development.

---

## Projects Overview

### 1. **Flight Delay Prediction**
**Objective**: Predict flight delays based on features like departure time, airline, origin, destination, and weather conditions.

- **Key Steps**:
  - **EDA**: Identifying patterns in flight delays and their contributing factors.
  - **Feature Engineering**: Creating time-related features, handling missing values, and encoding categorical variables.
  - **Models Used**: Linear Regression, Random Forest, XGBoost, CatBoost, LightGBM.
  - **Metrics**: Mean Absolute Error (MAE), Mean Squared Error (MSE).

- **Key Files**:
  - `flight_eda.ipynb`: Contains exploratory data analysis.
  - `flight_models.ipynb`: Machine learning models for flight delay prediction.

---

### 2. **House Price Prediction**
**Objective**: Predict house prices based on features such as location, square footage, number of bedrooms, and more.

- **Key Steps**:
  - **EDA**: Analyzing feature distributions and their relationship with house prices.
  - **Feature Engineering**: Handling missing data, encoding categorical features, and creating interaction terms.
  - **Models Used**: Ridge Regression, Lasso Regression, Gradient Boosting, Random Forest, XGBoost, LightGBM.
  - **Metrics**: Root Mean Squared Error (RMSE).

- **Key Files**:
  - `house_eda.ipynb`: Contains exploratory data analysis.
  - `house_models.ipynb`: Machine learning models for house price prediction.


## Getting Started

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook
- Required Python libraries (install via `requirements.txt`):
  ```bash
  pip install -r requirements.txt
  ```

### Installation
1. Clone the repository:
   ```bash
   (https://github.com/sasivirat/Machine_Learning_Projects.git)
   
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebooks:
   ```bash
   jupyter notebook
   ```

---

## Results

### Flight Delay Prediction
- **Best Model**: XGBoost Regressor with hyperparameter tuning.
- **Key Metrics**: 
  - Train R² Score: 0.89
  - Test R² Score: 0.86
  - Mean Absolute Error: 12.3 minutes.

### House Price Prediction
- **Best Model**: Gradient Boosting Regressor with hyperparameter tuning.
- **Key Metrics**: 
  - Train R² Score: 0.95
  - Test R² Score: 0.91
  - Root Mean Squared Error: $15,000.

---

## Highlights
- Clean, well-commented notebooks.
- Extensive data visualization and insights.
- Model benchmarking with multiple regression and ensemble methods.
- Hyperparameter tuning for optimal performance.

---

## Future Work
- Add deep learning models for house price prediction.
- Build to dashboard to visualize flight delay trends.

---

## Contributing
Feel free to submit issues or pull requests. Contributions are always welcome!

---

## License
This project is licensed under the [MIT License](LICENSE).

---

