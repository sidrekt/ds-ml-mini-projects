# Used Car Price Prediction

## Overview
This project predicts **used car prices** using both **traditional ML models** and a **neural network (MLP)**.  
It demonstrates how feature engineering, scaling, and deep learning can be combined to improve regression performance.

## Approach
- **Data Preprocessing**: Cleaning, encoding categorical variables, scaling numerical features (MinMaxScaler).  
- **Models**:
  - Random Forest Regressor (baseline)
  - Multi-Layer Perceptron (MLP) using PyTorch
- **Evaluation Metrics**: Mean Absolute Error (MAE), R² score.

## Results
- **MLP Model**:
  - MAE: 785  
  - R²: 0.88  

## Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- PyTorch  

## Usage
1. Clone the repository and navigate to the project folder:
   ```bash
   git clone https://github.com/your-username/ds-ml-mini-projects.git
   cd ds-ml-mini-projects/used-car-price-prediction
