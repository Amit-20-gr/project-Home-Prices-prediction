# project_Home_Prices_prediction
##Overview
This project focuses on predicting house prices in Bangalore based on historical house prices data. It involves several steps including data loading, data preprocessing, model building, and model evaluation. 
##Goals
Predict house prices accurately based on features such as square footage, number of bathrooms, number of bedrooms, and location.
Implement various machine learning algorithms to find the best-performing model.
Export the trained model for future use. 
##Steps Involved 
###1.Load Data 
Load the Bangalore house prices dataset into a pandas DataFrame.

###2.Handling Null Values 
Handle missing values in the dataset using appropriate techniques such as removal.

###3.Outlier Removal 
Identify and remove outliers from the dataset to improve model performance.

###4.Dimensionality Reduction  
reduce the dimension for location column.

###5.Convert Text to Numbers 
Convert textual feature'location' column to numerical values using one Hot Encoding.

###6.Building Model 
Implement machine learning algorithms such as Linear Regression, Lasso Regression, and Decision Tree Regression to predict house prices.

###7.Find Best Model Using GridSearchCV 
Use GridSearchCV to tune hyperparameters and find the best-performing model based on cross-validated performance.

###8.Export Model 
Export the trained model (Linear Regression in this case) for deployment or future use.

##Libraries Used 
.NumPy
.pandas
.matplotlib
.scikit-learn
##Results 
The Linear Regression model achieved an accuracy of over 80%, outperforming Lasso Regression and Decision Tree Regression.
Detailed results and evaluation metrics can be found in the project notebook.
