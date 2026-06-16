# Machine Learning:Regression Models

 [House Price Prediction: MLR vs Random Forest](https://github.com/Jack-Analyst5/Machine-Learning-Regression-Models/blob/main/Mission%204_%20Predicting%20House%20Price%20with%20Multiple%20Linear%20Regression%20%20(5).ipynb)

## Overview

This project compares the performance of two regression models, Multiple Linear Regression (MLR) and Random Forest (RF), in predicting house prices. The aim is to determine which model produces more accurate predictions based on the dataset.

---

## Goal

The study involves building predictive models using Multiple Linear Regression (MLR) and Random Forest (RF) techniques. The performance of these models is then evaluated using Root Mean Squared Error (RMSE) as the main metric. After assessing each model, their accuracy levels are compared to determine which performs better. Finally, different methods and approaches are identified to further improve overall model performance.

---

## Methodology

The methodology involves training two models, Multiple Linear Regression (MLR) and Random Forest (RF), to make predictions. Their performance is evaluated using Root Mean Squared Error (RMSE) and by visually comparing predicted values with actual values.


## Results
Through this project, I explored different modelling approaches to better understand how well they could capture patterns within the data. Both models were able to generate predictions that aligned reasonably well with actual outcomes, demonstrating their ability to learn from the dataset.
However, one model stood out with more consistent and reliable predictions. Its results were closer to the expected trend, which suggests that it was more effective in capturing the underlying relationships in the data. This comparison allowed me to see firsthand how different approaches can produce varying levels of accuracy, even when working with the same dataset.
Overall, the results gave me valuable insight into how model selection impacts performance and how important it is to evaluate models beyond just surface-level outcomes.

## Conclusion
This project reinforced the importance of experimenting with different analytical approaches to better understand data and improve predictive performance. While both models showed potential, the differences in their results highlighted how the structure of the data can influence which method performs best.
From a learning perspective, this experience helped me appreciate the full process of building and evaluating models—from preparing the data to interpreting the results. It also showed me that achieving better outcomes often requires continuous refinement, such as improving data quality, selecting meaningful features, and tuning models carefully.
Overall, this project was a valuable step in my development as a Data Analyst. It strengthened not only my technical skills, but also my ability to think critically about data, assess model performance, and communicate insights in a clear and meaningful way.

---

[Predictive Analytic Models]()

## Overview
This project presents a credit risk modelling initiative focused on classifying loan applications into approved (low-risk) and defaulted (high-risk) categories using machine learning techniques.

## Goal
The objective is to predict loan status from borrower data, using a binary classification approach where Class 0 represents low-risk loans and Class 1 represents high-risk loans; the dataset contains approximately 45,000 records with a 22% class imbalance toward high-risk cases.

## Methodology
The analysis uses borrower demographics, financial leverage, and credit history data, with exploratory analysis showing an average loan amount of $9,583, a mean interest rate of 11.0%, right-skewed loan distributions, and normally distributed credit scores; feature correlations highlight loan-to-income ratio and interest rate as key predictors, and three models—Logistic Regression, Gradient Boosting, and Random Forest—were evaluated.

## Results
Random Forest achieved the best performance with 92.87% accuracy, outperforming other models and delivering strong precision, recall, and F1-scores, with a confusion matrix showing high true negatives (6,797) and true positives (1,561), along with relatively low false positives (193) and false negatives (449).

## Conclusion
The model effectively predicts loan risk with high accuracy, supporting loss prevention through strong recall and ensuring fair approvals through high precision, providing a solid foundation for data-driven lending decisions and automated loan evaluation systems.
