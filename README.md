Walmart Sales Forecasting
Project Overview

Sales forecasting is a critical task for retail businesses as it helps optimize inventory management, workforce planning, and business strategy. This project uses Machine Learning techniques to predict weekly sales for Walmart stores based on store characteristics, economic indicators, holidays, and promotional markdowns.

Problem Statement

Retail businesses need accurate sales forecasts to make informed operational and financial decisions. The objective of this project is to build machine learning models that can predict weekly sales and identify the key factors influencing sales performance.

Dataset
Dataset: Walmart Sales Forecasting Dataset
Source: Walmart Historical Sales Data
Total Records: 421,570
Features: Store information, holiday indicators, economic factors, promotional markdowns, and sales data.
Target Variable: Weekly_Sales
Dataset Files
train.csv
stores.csv
features.csv

The datasets were merged using Store, Date, and IsHoliday attributes to create a unified dataset for analysis and modeling.

Tools and Technologies
Python
NumPy
Pandas
Matplotlib
Seaborn
Scikit-learn
Jupyter Notebook
Project Workflow
Data Loading
Dataset Merging
Data Cleaning
Missing Value Handling
Feature Engineering
Exploratory Data Analysis (EDA)
Data Preprocessing
Model Training
Model Evaluation
Sales Forecasting
Data Preprocessing
Merged multiple datasets into a single analytical dataset.
Handled missing values in promotional markdown columns.
Converted date columns into useful features such as:
Year
Month
Week
Encoded categorical variables.
Removed unnecessary columns.
Exploratory Data Analysis

The following analyses were performed:

Weekly Sales Distribution
Holiday vs Weekly Sales
Store Type vs Weekly Sales
Monthly Sales Trends
Impact of Economic Indicators
Promotional Markdown Analysis
Machine Learning Models Used
1. Linear Regression

A baseline regression model used for initial sales prediction.

2. Decision Tree Regressor

A tree-based model capable of capturing nonlinear sales patterns.

3. Random Forest Regressor

An ensemble learning model that combines multiple decision trees to improve prediction accuracy.

Model Performance
Model	MAE	RMSE	R² Score
Linear Regression	14,551.84	21,789.22	0.0896
Decision Tree Regressor	1,871.06	4,860.89	0.9547
Random Forest Regressor	1,487.16	3,798.63	0.9723
Key Insights
Store characteristics significantly influence weekly sales performance.
Promotional markdowns have a noticeable impact on sales.
Holiday periods contribute to fluctuations in sales trends.
Seasonal patterns can be observed through monthly sales analysis.
Economic indicators such as CPI and unemployment may influence customer purchasing behavior.
Best Model

Random Forest Regressor achieved the best performance:

MAE: 1,487.16
RMSE: 3,798.63
R² Score: 0.9723

The model explains approximately 97.23% of the variation in weekly sales, making it highly effective for sales forecasting.

Conclusion

A machine learning-based Walmart Sales Forecasting System was successfully developed using historical sales, store information, and economic indicators. Among the evaluated models, Random Forest Regressor achieved the highest predictive performance and provided highly accurate sales forecasts.

The developed system can assist retail organizations in improving inventory planning, staffing decisions, promotional strategies, and overall business forecasting.


Deepika B R

B.Tech Information Technology
Aspiring Data Scientist
Agni College of Technology