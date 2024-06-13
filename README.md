# Time-Series-Analysis-Apple-products-sales-analysis
Using Apple's product sales data set, we have implemented a combination of machine learning (ML) and time series algorithms to predict sales demand. Using available historical data, we used time series analysis methods such as moving average and exponential smoothing to capture and forecast sequential data such as daily, weekly or monthly sales trends. In addition,we used ML techniques to model the complex relationships between various factors affecting sales, such as number of orders and discounts. By integrating both ML and time series approaches, we aim to develop accurate and robust forecasting models that can predict sales demand with high accuracy and reliability.
# Data Abstract
This article examines dataset which is related to the data of 3 different apple products - MacBook Air, Air Pods and an apple watch and in which we forecast the sales demand of each product respectively. The dataset range is from 2018 to the year of 2019 and there are around 188340 records in our data with 10 distinct features. “sales” is our target variable
# Libraries
* pandas
* Numpy
* sklearn
* statsmodels
* seaborn
* matplotlib
* itertools
* holtwinters
# Time Series Forecasting Methods
* Moving Average
* Weighted Moving Average
* Naive Approach
* Exponential Smoothing
* Double Exponential smoothing
* Triple exponential Smoothing
# ML Models
* Linear Regression
* Decision Tree Regressor
# Data Preprocessing
* Exploratory Data Analysis (EDA) - Univarate Analysis, Multivariate Analysis
* Outliers detection - IQR Method (Box Plot).
* Outliers prevention - Log Transformations
* Data Exploration & distribution - Summary Statistics & Histogram.
* Hyperparameter Tuning - GridSearchCV to compute optimal value of alpha, beta and gamma. 
* Model Evaluation - Computing 'RSFE', 'MAE', 'MSE', 'RMSE', 'MAPE', 'MPE'.
# Advantages
* Inventory management: This forecasting helps in optimizing inventory levels according to its sales predictions. With prediction, they get to know about the demand which will arise in future. According to the demand, they can order/manage inventories. It helps in determining the optimal order quantity that minimizes total inventory costs, including holding costs and ordering costs. It considers factors such as demand variability, lead time, and ordering costs.
* Enhance production planning: By predicting the future sales, company may know how much production for one particular product needs. Once they get the approximate number they can manage their production line in good manner. The model evaluates potential suppliers based on multiple criteria such as quality, cost, reliability, and lead time. Each criterion is assigned a weight reflecting its importance to the organization.
* Finance management: With these forecasting methods, they can estimate their finance according to the predictions. For example, exponential smoothing is suitable for forecasting when there is a need to react quickly to changes in demand patterns. It gives more weight to recent data points while gradually decreasing the influence of older observations.Moreover, it helps to view overall growth of companies in its near future.
