# Regression-Models

 House Price Prediction: MLR vs Random Forest

## Overview

This project compares the performance of two regression models, Multiple Linear Regression (MLR) and Random Forest (RF), in predicting house prices. The aim is to determine which model produces more accurate predictions based on the dataset.

---

## Goal

The study involves building predictive models using Multiple Linear Regression (MLR) and Random Forest (RF) techniques. The performance of these models is then evaluated using Root Mean Squared Error (RMSE) as the main metric. After assessing each model, their accuracy levels are compared to determine which performs better. Finally, different methods and approaches are identified to further improve overall model performance.

---

## Project Structure

## Visualisation:
--
''
images/rf_plot.png
*Figure 1: Random Forest Predictions vs Actual Values*
``



## Methodology

Two models were trained:

- Multiple Linear Regression (MLR)  
- Random Forest (RF)  

Evaluation metrics:

- Root Mean Squared Error (RMSE)  
- Visual comparison of predicted vs actual values  

---

## Results

- MLR RMSE: 63,952  
- RF RMSE: 72,013  

Observations:

- Both models show strong correlation between predicted and actual values  
- MLR predictions are closer to the perfect prediction line  
- Estimated prediction error (on a 600,000 house):
  - MLR: ~10.6%  
  - RF: ~12%  

MLR performed better, suggesting a mostly linear relationship in the data.
---

## Improvements

### Multiple Linear Regression

- Feature engineering (e.g., price per square foot)  
- Outlier removal  
- Multicollinearity checks  

### Random Forest

- Hyperparameter tuning  
- Feature selection  


## Conclusion

The Multiple Linear Regression model outperformed the Random Forest model on this dataset. The results indicate that the underlying relationships in the data are largely linear.

Further improvements can be achieved through better feature engineering, tuning, and validation techniques.
