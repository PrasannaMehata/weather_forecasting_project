🌦️ Global Weather Trend Forecasting
Data Science • Machine Learning • Time Series • Geospatial Analysis
This project analyzes the Global Weather Repository dataset and performs weather forecasting, climate analysis, advanced EDA, and spatial modelling.

📁 Dataset
The dataset is sourced from Kaggle:

Global Weather Repository
https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository

It contains daily global weather information with 40+ features, including:
Temperature
Humidity
Precipitation
Wind Speed
Air Quality Metrics
Geographical Metadata
Timestamps (lastupdated)

📌 1. Data Cleaning & Preprocessing

Performed cleaning steps:

Converted lastupdated to datetime
Sorted and indexed data chronologically
Filled missing values using median imputation
Removed duplicate entries
Outlier removal using Z-score
Normalization using MinMaxScaler
Prepared city-level subsets for forecasting

📌 2. Exploratory Data Analysis (EDA)

Visualized:
Temperature trends
Precipitation patterns
Correlation heatmaps
Distribution plots of major weather parameters
These insights helped understand global and regional weather behavior.

📌 3. Advanced EDA

Implemented Anomaly Detection using:

Isolation Forest
Detected unusual temperature spikes
Marked outlier regions for further inspection

📌 4. Time Series Forecasting Models

Forecasts were generated for selected cities (example: London).
Implemented multiple forecasting models:
🔹 ARIMA (Auto-Regressive Integrated Moving Average)
Used classical statistical modeling for 30-day temperature forecasting.
🔹 Prophet
A Facebook/Meta forecasting package for trend + seasonality modeling.
🔹 Ensemble Model
Combined results from ARIMA + Prophet using simple averaging for higher accuracy.

📌 5. Climate Analysis

Studied long-term temperature trends by:
Extracting year-wise averages
Visualizing global warming patterns
Detecting climate shifts across decades

📌 6. Environmental Impact Analysis (Air Quality Correlation)

Computed correlations between:
PM values (air quality indicators)
Weather features such as temperature, humidity, wind speed
Heatmaps revealed potential interactions between pollution and weather.

📌 7. Feature Importance (Machine Learning)

Used Random Forest Regressor to identify top predictors of temperature.
This helped uncover:
Which weather parameters influence temperature most
Potential features to use in downstream models

📌 8. Spatial Analysis (Choropleth Maps)

Used Plotly to create interactive world maps showing:
Country-wise average temperature
Spatial patterns of climate variability
Regional differences across continents

📌 9. Deliverables

The project includes:

✔ Full data cleaning workflow
✔ EDA visualizations
✔ Forecasting models with performance metrics
✔ Climate trend study
✔ Air quality analysis
✔ Spatial weather visualization
✔ Anomaly detection
✔ Feature importance charts
✔ Final ensemble forecasting output


🛠️ Technologies Used
Languages:
Python
Libraries
Pandas, NumPy
Matplotlib, Seaborn
Plotly
Scikit-learn
Prophet
Statsmodels (ARIMA)
Isolation Forest
MinMaxScaler


📊 Example Outputs
✔ Temperature & Precipitation Trends
✔ Global Choropleth Weather Map
✔ Climate Change Curve
✔ Anomaly Detection Scatter Plot
✔ Feature Importance Bar Chart
✔ ARIMA + Prophet Ensemble Forecast


