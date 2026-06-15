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

### Random Forest Model
rf_model.png
*Figure 1: Random Forest Predictions vs Actual Values*

### Multiple Linear Regression Model
mlr_model.png
*Figure 2: Multiple Linear Regression Predictions vs Actual Values*



## Methodology

The methodology involves training two models, Multiple Linear Regression (MLR) and Random Forest (RF), to make predictions. Their performance is evaluated using Root Mean Squared Error (RMSE) and by visually comparing predicted values with actual values.


## Results

The results show that the Multiple Linear Regression (MLR) model achieved an RMSE of 63,952, while the Random Forest (RF) model recorded a higher RMSE of 72,013. This indicates that MLR performed better overall. Both models demonstrate a strong correlation between predicted and actual values; however, the MLR predictions are closer to the ideal perfect prediction line, suggesting higher accuracy. Based on a house valued at 600,000, the estimated prediction error is approximately 10.6% for MLR and around 12% for RF, further confirming that MLR provides more precise predictions in this case.



## Conclusion

The results indicate that the Multiple Linear Regression (MLR) model outperformed the Random Forest (RF) model on this dataset, suggesting that the relationships between the variables are largely linear. While both models demonstrated reasonable predictive capability, MLR achieved better accuracy as reflected in its lower RMSE. Further improvements in model performance can be achieved through techniques such as feature engineering, outlier removal, and checking for multicollinearity in MLR, as well as hyperparameter tuning and feature selection in RF. Overall, refining these approaches can enhance the reliability and accuracy of the predictive models.
