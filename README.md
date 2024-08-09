# Supervised-Machine-Learning
Creating a predictive model for house sale prices using property features. The model helps sellers set competitive price, aids buyers in fair purchases.
This project showcases advanced feature engineering and transformation techniques applied to a preprocessed housing dataset. After completing thorough data exploration and preprocessing, further steps were taken to optimize the dataset for linear regression modeling.
# Libraries Used:
NumPy: For numerical operations and array manipulation.
Pandas: For data manipulation and analysis, particularly DataFrames.
Matplotlib: For data visualization and plotting graphs.
Scikit-learn (sklearn): For machine learning algorithms and preprocessing tasks
# Key Highlights:
# Data Exploration and Preprocessing:
Conducted univariate and bivariate analysis to understand individual variables and their relationships.
Applied imputation techniques to treat outliers and manage missing values, ensuring data quality and consistency.
Addressed issues like data normalization and created dummy variables for categorical features.
# Log Transformation:
Applied log transformation to several continuous variables that were right-skewed to reduce skewness and improve normality. This included:
Transformed Flat Area
Transformed Basement Area
Transformed Living Area
# Feature Engineering:
Luxury Home Indicator: Introduced a new binary feature, luxury_home, based on the presence of a waterfront view, house condition (excellent or good), and an overall grade of 8 or higher. This feature was encoded as 1 for luxury homes and 0 for non-luxury homes.
Binning: Performed binning on the Age of the House variable to categorize homes into different age groups, making the feature more interpretable for analysis.
One-Hot Encoding: Applied one-hot encoding to categorical variables to make the dataset fully compatible with linear regression models.
These transformations and feature engineering steps have significantly enhanced the dataset, making it more suitable for linear regression and improving the predictive power of the model.

