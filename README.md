# Prediction-with-KNN-Classification
Implementation of KNN algorithm in Python 3 for prediction of Target class.

# Description
* K-Nearest-Neighbors algorithm is used for classification and regression both.
* In this project, it is used for classification.
* Classified dataset used to predict target class.

# Data set format
* CSV (Comma Separated Values) format.
* Attributes can be integer or real values.
* Responses can be integer, real or categorical.

# Overview
The primary goal is to predict target class based on multiple independent variable.

# liabrary 
* pandas, numpy, matplotlib,seaborn,sklearn,joblib used in project

# Methodology
1. ## Machine learning life cycle:
   - followed indistry standard practice of machine learning life cycle steps.
2. ## Preprocessing and EDA:
   - implement necessary transformation, preprocessing of dataset.
   - conduct exploratory data analysis on dataset.
3. ## Visualization:
   - visualised data using visualisation library like matplotlib, seaborn.
4. ## Algorithm:
   - scikit library use for KNN algorithm.
5. ## model validation:
   - model validate with accuracy score of diff K, confusion metrix.
6. ## save model:
   - joblib library used to dump model.
   - model is saved in .ipynb formate as i_phone_purchase_product_using_KNN_model.
# EDA is not done in project, due to focus on machine learning only.

# KNN model:
- K value  by standard method is 31.
- K value by error method is 18 , so we considered 17 or 19 as odd number.
- model build with all k values and checked accuracy score and confusion metrix.
- with K=31, accuracy score is 94.5%
- with k=17, accuracy score is 95.5%
- with k= 19, accuracy score is 96.5%
- so accuracy in k=19 is better, so this model is saved and loaded to predict. 
