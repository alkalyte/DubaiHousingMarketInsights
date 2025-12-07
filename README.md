**Price Prediction of Residential Houses in Dubai Housing Market**
This project analyzes real housing transaction data from Dubai and builds a machine learning model to predict selling price based on property features.
**Objectives:**
-Explore the Dubai housing dataset
-Clean and preprocess data
-Visualize market trends
-Build predictive models (Linear Regression & Random Forest)
-Evaluate model performance
-Predict price for new input data
**Technologies Used**
-Excel
-Python
-Pandas
-Matplotlib
-Seaborn
-Scikit-Learn
**Files Included**
-dubai_housing_project.ipynb – Main project notebook
-DubaiProjectDataSet.csv – Dataset used in the project
-The dataset is originally collected from https://www.opendatabay.com/data/financial/7186b07f-79ec-42da-b83e-6cf7d664e726
**Machine Learning Algorithms Used**
-Linear Regression
-Random Forest Regressor
**Model Output**
This project explored real housing transaction data from Dubai, performed data cleaning and EDA, and built machine learning models to estimate the selling price of a property.
From the analysis, built‐up area (sqft) and sale price per foot were found to be the strongest numerical factors influencing selling price. Other features such as bedrooms, parking, and year showed weaker effects in comparison. The month feature showed small variations in predicted prices, which may indicate seasonal patterns or peak transaction periods in the Dubai real estate market.
For modelling, both Linear Regression and Random Forest Regressor were tested.
Random Forest performed significantly better (R²: ~0.99, MAE: ~8,439 AED).
This indicates that the final model can provide reasonably accurate price estimates for properties with similar numerical characteristics in the dataset.
An example prediction function was also added to demonstrate how users can input new property details (sqft, bedrooms, parking, month, price per foot, etc.) to obtain a predicted selling price.
