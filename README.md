# superstore_analysis
internship project

Sales Trend Analysis from Superstore Dataset
This project performs time-series analysis on monthly sales data extracted from the popular Superstore dataset. It aims to identify overall trends, smooth fluctuations, and detect anomalies using linear regression and residual analysis.

 Dataset
File used: Sample - Superstore.csv
Source: kaggle repositroy
Encoding: "latin1"
The dataset contains sales records across regions, categories, and dates.

 Tools & Libraries Used
Pandas – Data loading & preprocessing
Matplotlib  – Visualization
Statsmodels – Linear regression, seasonal decomposition
Datetime – Time index manipulation

 Steps Performed
Data Preprocessing
Convert Order Date to datetime and set it as the index.
Resample the data to monthly frequency (ME - Month End).
Apply a 3-month rolling average to smooth the sales data.

Decomposition 
Decomposes the series into trend, seasonality, and residuals using multiplicative model.
Trend Detection
Seasonality Detecttion
Noise 

Anomalies 
uses simple linear regression(OLS) to find anomalies which are not present in the project 
![image](https://github.com/user-attachments/assets/d82e26c4-ff7b-4f78-a8af-e73fbc4df219)



