Diabetes Dataset Regression Analysis With Regularization Techniques Lab

Name: Shyam Nath
Course Title: Advanced Big Data and Data Mining (MSCS-634-M40)  
Lab Assignment: Lab 4- Regression Analysis with Regularization Techniques  


Overview

This lab explores a range of regression techniques using the Diabetes dataset from `sklearn.datasets`. The main objectives are to implement and compare:
- Simple Linear Regression
- Multiple Regression
- Polynomial Regression
- Ridge Regression
- Lasso Regression

Evaluating model performance using metrics such as MAE, MSE, RMSE, and R², and visualizing predictions to deepen the understanding of overfitting and regularization.


Files Included

- Lab_4_Regression_Analysis.ipynb  
  Jupyter Notebook containing all code, outputs, and visualizations for the regression analysis.

- README.md  
  This file, summarizing the lab purpose, key insights, and any notable challenges or decisions.


Purpose

The goal of this lab is to:
- Practice implementing various regression models.
- Understand the role of regularization in preventing overfitting.
- Develop skills in model evaluation and interpretation using real-world health data.


Key Insights

-Simple Linear Regression with one feature (e.g., BMI) gave limited prediction power, highlighting the need for more information to accurately model diabetes progression.
-Multiple Regression using all features significantly improved performance, demonstrating the value of multivariate modeling.
-Polynomial Regression added nonlinearity but risked overfitting with higher degrees.
-Ridge and Lasso Regression helped prevent overfitting and improved model generalization by regularizing model coefficients. Lasso also encouraged sparsity (some coefficients set to zero).


Challenges and Decisions

- Selecting the appropriate polynomial degree was tricky: higher degrees can fit the training data better but hurt generalization.
- Choosing optimal alpha (regularization strength) for Ridge/Lasso required experimentation.
- Visualizing and interpreting results helped diagnose overfitting and underfitting.
