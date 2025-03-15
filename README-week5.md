# Vehicle Pricing Analysis Project

# Business Understanding

The goal of this project is to analyze the factors that influence vehicle pricing and develop predictive models to estimate vehicle prices based on attributes such as year, make, model, condition, and odometer reading.

# Business Questions

Which factors significantly impact vehicle prices?

Helps sellers price vehicles competitively and buyers negotiate effectively.

How accurate are machine learning models in predicting vehicle prices?

Enables optimized pricing strategies for dealers and resale platforms.

What actionable recommendations can be made to improve vehicle sales?

# Success Criteria

Development and evaluation of multiple predictive models.

Clear insights into vehicle pricing trends through statistical analysis and visualizations.

Actionable recommendations for stakeholders presented in an understandable manner.

# Data Preparation

Loaded dataset (vehicles.csv) and performed data cleaning.

Removed unnecessary columns and imputed missing values.

Transformed categorical variables using label encoding.

Created a binary classification target variable (price_category).

# Exploratory and Statistical Analysis

Conducted correlation analysis (Pearson and Spearman) among key features.

Identified significant correlations between vehicle attributes (year, odometer, cylinders) and price categories.

Visualized correlations through heatmaps.

# Modeling Approach

Classification Models

Logistic Regression

Random Forest

XGBoost

Hyperparameter tuning performed using GridSearchCV, with performance validated with cross-validation.

# Model Performance

Evaluated models using classification reports and cross-validation scores.

Random Forest provided higher accuracy compared to Logistic Regression and XGBoost.

# Feature Importance

Utilized Random Forest Regressor to identify influential features.

Year, condition, odometer, and cylinders emerged as significant contributors to vehicle price determination.

Visualized feature importance clearly with bar charts.

# Visualization

Created comprehensive visualizations:

Price Distribution (histogram)

Price vs. Year (scatter plot)

Price vs. Condition (box plot)

Price vs. Cylinders (box plot)

# Future Price Predictions

Predicted median vehicle prices from 2020 to 2150 using Linear Regression.

Forecast showed trends clearly through visualizations, providing stakeholders insight into future pricing scenarios.

# Actionable Recommendations

Prioritize condition and mileage improvements before resale.

Market newer vehicle models aggressively, leveraging increasing price trends.

Dealers can leverage predictive insights to optimize inventory management and pricing strategies.

# Conclusion

The project successfully identified influential price factors and demonstrated high accuracy in price prediction models.

Stakeholders can use these insights to enhance decision-making regarding vehicle sales and purchases.
