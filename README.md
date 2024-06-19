## Solar Irradiance Prediction

Welcome to the Solar Irradiance Prediction project repository! This project leverages meteorological data from the HI-SEAS weather station to forecast solar radiation. By analyzing factors such as temperature, humidity, wind speed, and barometric pressure, the goal is to predict solar irradiance, crucial for estimating solar energy potential.

<img src="https://drive.google.com/uc?id=117aEsq4apS8lplV-hCQLR7VPy2XTiRaf" width="600" height="400">

### Key Features

- **Dataset:** Utilizes HI-SEAS weather station data spanning four months (September to December 2016).
  
- **Data Processing:** Includes data wrangling to extract relevant time and meteorological features, and feature selection methods like correlation matrix analysis and SelectKBest.

- **Feature Engineering:** Implements transformations such as BoxCox, Log, MinMax, and Standard to enhance predictive accuracy.

- **Modeling:** Utilizes machine learning techniques including XGBoost for gradient boosting and a multilayer perceptron (MLP) for neural network-based predictions.

### Libraries Used

- **Python Libraries:** `numpy`, `pandas` for data manipulation; `scikit-learn` for feature selection, preprocessing, and modeling; `xgboost` for gradient boosting; and `tensorflow` or `keras` for MLP implementation.


### Usage

1. Clone the repository and navigate to the project directory.
2. Explore Jupyter notebooks for step-by-step implementation and experimentation with different models and techniques.
3. Contribute by opening issues or pull requests for enhancements or suggestions.

