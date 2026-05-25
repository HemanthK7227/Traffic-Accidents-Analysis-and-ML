# Analyzing Key Factors in Traffic Accidents

## Project Overview
This project analyzes traffic accident data to identify key risk factors, predict accident severity, and recommend data-driven road safety improvements.

## Business Problem
Traffic accidents are influenced by multiple factors such as weather, speed, road quality, traffic signals, and vehicle count. This project uses data analytics and machine learning to understand how these factors impact accident severity.

## Objectives
- Identify high-risk conditions contributing to severe accidents
- Analyze accident trends by time, location, and road conditions
- Build machine learning models to predict accident severity
- Recommend safety improvements for high-risk areas

## Dataset
**Source:** Kaggle - Key Factors in Traffic Accidents

Key fields include:
- Accident time and location
- Weather conditions
- Road quality indicators
- Vehicle count
- Accident severity metrics

## Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost, CatBoost, Random Forest
- Ridge & Lasso Regression
- Matplotlib / Seaborn
- Feature Engineering
- Machine Learning

## Methodology
1. Cleaned missing values and treated outliers
2. Encoded categorical variables
3. Standardized date and time fields
4. Created custom features such as Accident Impact
5. Applied MinMaxScaler for normalization
6. Built and compared multiple ML models
7. Evaluated models using R² Score, MSE, and RMSE

## Model Performance
The Voting Regressor performed best with:

- **R² Score:** 0.8453
- **RMSE:** 2.03
- **Cross-validation:** 10-fold validation

## Key Insights
- Poor pavement conditions, rain, and high speed increase accident severity
- Evening and night periods show higher accident frequency
- Traffic light presence, vehicle speed, and vehicle count were key predictive features
- Urban intersections and congested areas had higher accident density

## Recommendations
- Improve lighting and signage in high-traffic urban areas
- Enforce stricter speed controls on poor-quality roads
- Optimize traffic signal timing based on accident history
- Launch safety campaigns during weekends, rainy days, and night hours

## Conclusion
This project demonstrates how machine learning and data analytics can help predict accident severity, identify risk factors, and support smarter traffic safety planning.
