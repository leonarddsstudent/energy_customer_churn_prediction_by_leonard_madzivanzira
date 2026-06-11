# Customer Churn Prediction

# Project Overview
This projets predict whether a customer is likely to churn (leave a service) using machine learning techniques. The goal is to help businesses identify at-risk customers early and improve retention strategies.

-------

## Dataset
The dataset contains customer behaviour and service usage features such as:
- Tenure
- consuption levels
- Net margin
- Forecast consumption
- Service usage patterns
- Discount given
- Days before end of contract

-------

## Data Preprocessing
- Handled missing values
- Encoded categorical variables
- Feature engineering(for example tenure days, activation month)
-------

## Model used
- Random Forest Classifier

-------

## Feature importance
The most influencial features in predicting churn were:
1. Net margin
2. Consumption in 12 months
3. Forecast metre rent
4. Forecast consumption in 12 months
5. Days to end

------

## Evaluation Metrics

Classification Report:
              precision    recall  f1-score   support

           0       0.91      1.00      0.95      2638
           1       0.83      0.08      0.15       284

    accuracy                           0.91      2922
   macro avg       0.87      0.54      0.55      2922
weighted avg       0.90      0.91      0.87      2922

-------

## Results
 Feature Importance
1.                                net_margin    0.053142
2.                                   cons_12m   0.052171
3.                    forecast_meter_rent_12m   0.051260
4.                          forecast_cons_12m   0.049822
5.                        margin_net_pow_ele    0.049366
6.                      margin_gross_pow_ele    0.048187
7.                               days_to_end    0.047203
8.                   days_since_modification    0.043949
9.               var_year_price_off_peak_var    0.039164
10.                   var_year_price_off_peak   0.038955


-------


## Key Insights
- Customers with high net margin are likely to churn than those with low net margin accroding to the results
- Customers with high consumption are unlikely to churn than those with low consumption
- Days before the end of contract is also a predictor of churn

-------

## Tech Stack
- Python
- Pandas
- Scikit-learn


# Summary
Developed a customer churn predition model using Random Forest and Feature Engineering techniques. Achieved a 91% accuracy and identified key drivers of customer attrition including net margin, tenure and energy consumption patterns. Generated actionable business rcommendations to support customer retention strategies

-------

## Author
Leonard Madzivanzira

Aspiring Data Scientist | Machine Learning Enthusiast








- ------
