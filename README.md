# BultyDolui-Introduction-to-Data-Science
Project 1
Overview
This project focuses on analyzing and forecasting personal financial data using Python. The goal is to identify spending patterns, track financial habits, and build a predictive model that forecasts future expenses and savings. The project demonstrates the application of time series analysis and ARIMA (AutoRegressive Integrated Moving Average) modeling to make data-driven financial decisions.

Objectives
Analyze trends in personal finance data, including income, expenses, and savings.
Explore monthly and yearly spending patterns to identify high-expense categories.
Build a forecasting model using ARIMA to predict future expenditure trends.
Visualize financial trends and model predictions using charts and plots.
Demonstrate the application of statistical and mathematical concepts in real-world financial analytics.

Methodology
Data Preprocessing:
Loaded and cleaned personal finance datasets.
Converted transaction dates into time series format.
Handled missing values and outliers.
Exploratory Data Analysis (EDA):
Analyzed spending distribution by category and time period.
Visualized trends using line plots, bar charts, and seasonal decomposition.
Time Series Modeling:
Conducted stationarity tests using ADF (Augmented Dickey–Fuller).
Applied ARIMA model for time series forecasting.
Tuned parameters (p, d, q) based on AIC and PACF/ACF plots.
Forecasted future expenses and visualized predictions against actual data.
Evaluation:
Assessed model performance using MAE, RMSE, and visual error analysis.
Interpreted forecast results to support better financial planning.

Tech Stack
Python
Pandas, NumPy – for data cleaning and manipulation
Matplotlib, Seaborn – for visualization
Statsmodels (ARIMA) – for time series modeling and forecasting

Key Insights
Identified spending seasonality (e.g., higher expenses during holidays or specific months).
Built an ARIMA model that successfully forecasted upcoming monthly expenses with strong accuracy.
Highlighted how predictive analytics can enhance personal financial decision-making.

Future Enhancements
Extend forecasting with SARIMA or Prophet for seasonality-aware predictions.
Integrate real-time expense tracking using APIs or financial dashboards.
Automate monthly forecast generation and visualization.

Project 2
Electric Consumption Analysis
Objective:
Analyze and understand patterns in electricity consumption data to identify usage trends and influencing factors such as time, temperature, and household characteristics.

Highlights:
Collected and cleaned energy consumption data for exploratory analysis.
Investigated how factors like season, time of day, and weather affect consumption levels.
Performed data visualization to highlight high and low consumption periods.
Applied correlation and regression analysis to predict electricity usage.
Demonstrated applications of data preprocessing, feature scaling, and model evaluation in energy analytics.

Tech Stack: Python · Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn

Key Insights:
Identified daily and seasonal usage patterns.
Found strong correlation between temperature and energy usage.
Created regression models that effectively estimate future consumption trends.
