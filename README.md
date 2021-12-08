# Project 2: Ames Housing Prices Analysis

### Problem Statement

- Which features will make for a good investment in Ames

We were tasked with creating a machine learning model using the Ames Housing Dataset. This dataset contained 82 columns of different features and 2,930 observations, 2051 of which were used to train our model. 

### Executive Summary

I began by reading in and inspecting my data, using various bar chart and heatmaps. During this step, I made sure to analyze the amount of missing values we had in each feature. Next, I analyzed features and their correlations and relationships with price and other features. I then cleaned my data by dropping unneeded columns, dealing with empty values, looking for multicollinearity, eliminating outliers, and finally replacing nominal categorical data with numbers. I added some features and then created my models, incorporating Lasso Regression and Ridge Regression and an analysis of the coefficients they created. Lastly, I explained my insights and conclusions.

### Contents:
- Load in and Inspect the Data
- Examine Features
- Clean Data
    - Drop Unneccessary Columns
    - Deal with NaN Values
    - Look for Multicollinearity
    - Remove outliers 
    - Replace Nominal Categorical Data with Numbers
- Feature engineering
    - Interaction Features
    - Remove more Features
- Save Clean Data
- Model 
   - Read in Clean Data
   - Create X and y
   - Model with Standard Scaler and Ridge with OHE
   - Model with Standard Scaler and Lasso with OHE
   - Categorical Column Transformation with Dummies
   - Model with Standard Scaler and Ridge with Dummies
   - Model with Standard Scaler and Lasso with Dummies
- Conclusion

### Data Dictionary

The data dictionary with feature descriptions: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt

### Conclusion

Kaggle Model: Both the Lasso and the Ridge model performed very well, but Lasso ended up being the best model with an R^2 score of about .92, suggesting the model explains about 92% of the variance in sales price for the training data.

Business Recommendations: Based on initial analysis and the coefficients of the models used for the Kaggle Competition, it appears homebuyers should look for homes that have a good quality score, have high square footage, and are located good neighborhoods, such as in Northridge, Stone Brook, or Northridge Heights.