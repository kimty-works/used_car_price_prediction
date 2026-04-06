# used_car_price_prediction
AI BigData Academy A4 India used car market price prediction modeling

## Project Introduction
Used Car Price Prediction Model&Market Entry Strategy

## Team Introduction
- Tayoung Kim : Leader, EDA, Multiple Regression Modeling, Feature Engineering
- MS Kim : EDA, Nonparametric Deep Learning Model, Feature Engineering
- RH Kim : EDA, Nonparametric Deep Learning Model, Feature Engineering
- SY Yun : EDA, Nonparametric Deep Learning Model, Feature Engineering
- JH Park : EDA, Nonparametric Deep Learning Model, Feature Engineering
- YJ Lee : EDA, Nonparametric Deep Learning Model, Feature Engineering

## Data
Used Car Market Data from India (n = 7,253; 11 independent variables; dependent variable: log_price)

## Methodology  
1. Data Preprocessing  
   - Handled missing values and outliers  
   - Generated derived variables based on domain knowledge  

2. Feature Selection  
   - Conducted statistical tests to remove insignificant variables  
   - Addressed multicollinearity issues  

3. Data Analysis  
   - Applied multiple linear regression (OLS)  
   - Performed residual analysis and model diagnostics  
   - Implemented nonparametric machine learning models  

4. Model Development  
   - Built and evaluated Gradient Boosting model  
   - Compared performance across different models  

## Result
Model Selection : Gradient Boosting Model(R2 :0.89, MSED:0.09, 5-Fold CV Mean : 0.8946)

## Insight
#### Model Insight
The top two most important variables explain approximately 80% of the model’s overall predictive power. Engine output is identified as a key driver of premium pricing, while vehicle age serves as a major factor contributing to price depreciation.

#### Business Insight
These findings, when combined with real market data, suggest strong potential for developing a customized pricing recommendation system based on variable-level price sensitivity.
