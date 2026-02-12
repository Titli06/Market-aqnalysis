# Real Estate Price Prediction & Market Analysis

## Objective
Analyze real estate transaction data and build a machine learning model to predict housing prices and identify the major factors influencing property valuation.

## Dataset
Bengaluru housing dataset containing 13,000+ property records with features such as location, size, total_sqft, bath, and price.

## Workflow
1. Data Cleaning
   - Removed missing values
   - Handled outliers
   - Standardized 240+ location categories

2. Exploratory Data Analysis
   - Correlation heatmap
   - Price distribution
   - Location-wise price trends

3. Feature Engineering
   - Price per square foot
   - Location grouping

4. Modeling
   - Linear Regression
   - Lasso Regression
   - Decision Tree

## Evaluation
Model evaluated using R² score and RMSE.  
Best model achieved ~0.81 R².

## Key Insights
- Location is the strongest predictor of housing price
- Price per square foot improves prediction significantly
- Removing extreme outliers improves model stability

## Tools Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
