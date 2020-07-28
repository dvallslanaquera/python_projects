# David Valls Portfolio
Welcome to my personal portfolio. Here you can find some scripts showing a portion of the last projects I've been carrying out. 
You can explore the different projects by clicking on any hyperlink below.

## Personal Resume:
* [**English version**](https://github.com/dvallslanaquera/python_projects/blob/master/images/David%20Valls%20Lan%C3%A0quera%20-%20Resume.pdf)
* [**日本語版**](https://github.com/dvallslanaquera/python_projects/blob/master/images/%E5%B1%A5%E6%AD%B4%E6%9B%B8%20-%20David%20Valls.pdf)

## Project 1: [House Sale Price Prediction](https://github.com/dvallslanaquera/house_sale_prediction/blob/master/House%20Prices%20(definitive%20edition).ipynb)
![](https://github.com/dvallslanaquera/python_projects/blob/master/images/housesbanner.png)
* Thorough preprocess steps explained with detail were we managed to clean all missing values, outliers and skewness using cutting-edge techniques such as Yeo-Johnson Power Transformation.
* Feature selection process included using Recursive Feature Elimination (RFE)
* **Stacked predictive model** with prompts the average of three tunned models: XGBoots, LightGBM and Gradient Booster.
* Final **RMSE of 0.1139** (std = 0.0053). The result has been cross-validated with a 10-fold Cross Validation algorithm.  

## Project 2: [Heart Attack Classificatory Prediction](https://github.com/dvallslanaquera/heart_condition_classification/blob/master/Heart%20Attack%20Chance.ipynb)
* Thorough preprocess steps explained with detail were we managed to clean all missing values, outliers and skewness using cutting-edge techniques such as Yeo-Johnson Power Transformation.
* Feature selection process including a Feature Importance plot using XGBoost model. 
* Grid search process explained with detail from scratch up to the last step. 
* **Stacked predictive model** with prompts the average of five tunned classificatory models: Logistic Regression, ExtraTrees, Random Forest, KNN and SVC.
* Final **normalized Gini score of 0.854** (std = 0.0071). The result has been cross-validated with a 10-fold Cross Validation algorithm.  
![](https://github.com/dvallslanaquera/resume_davidvallslanaquera/blob/master/images/auc.jpeg)

## Project 3: [E-commerce RFM analysis](https://github.com/dvallslanaquera/ecommerce_rfm/blob/master/e-commerce-clustering-rfm-analysis.ipynb)
![](https://github.com/dvallslanaquera/python_projects/blob/master/images/worldmappng.png)
* Comprehensive EDA and feature engineering preprocessing
* PCA dimensionality reduction applied before a k-means clustering for high-dimensional data
* RFM analysis created from scratch
