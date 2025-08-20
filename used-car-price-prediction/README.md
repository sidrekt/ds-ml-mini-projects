# Used Car Price Prediction

This project predicts **used car prices** based on features such as brand, mileage, engine size, fuel type, accidents, and service history.  
It uses a machine learning pipeline with **Random Forest** and **Neural Network (MLPRegressor)** models, along with preprocessing for categorical and numerical variables.  

## 🚀 Features
- Data preprocessing with handling missing values (`service_history`).
- Feature engineering: adding `car_age` from `make_year`.
- Encoding categorical features with `OneHotEncoder`.
- Scaling numerical features with `StandardScaler`.
- Model training with:
  - **Random Forest Regressor**
  - **Neural Network (MLPRegressor)**
- Model evaluation using MAE and R² score.
- Correlation analysis and visualization with `seaborn` and `matplotlib`.

## 📂 Dataset
The dataset (`used_car_price_dataset_extended.csv`) includes columns such as:
- `brand`
- `fuel_type`
- `transmission`
- `mileage_kmpl`
- `engine_cc`
- `owner_count`
- `accidents_reported`
- `insurance_valid`
- `service_history`
- `make_year`
- `price_usd` (target variable)

## ⚙️ Installation

Clone this repository and install dependencies:

```bash
git clone https://github.com/sidrekt/ds-ml-min-projects.git/used-car-price-prediction
cd used-car-price-prediction
pip install -r requirements.txt
