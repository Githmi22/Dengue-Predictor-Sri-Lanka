### Pattern Recognition and Predicting Dengue Outbreaks in Sri Lanka Using Machine Learning and Weather Data

## 🧠 Overview
This research project investigates the application of machine learning models to predict dengue outbreaks in Sri Lanka using historical weather and epidemiological data. The study explores the relationship between climatic factors—such as rainfall, temperature, and humidity—and the incidence of dengue fever, aiming to provide an early warning system that enhances public health response and resource allocation.

## 🎯 Objectives
Develop accurate predictive models to forecast dengue outbreaks.
Integrate weather data (2010–2024) and dengue case data (2010–2020) into a unified analytical framework.
Evaluate traditional and advanced machine learning techniques, including ARIMA and XGBoost.
Identify the most influential weather features in dengue transmission.

## 📊 Data Sources
Dengue Case Data: Epidemiology Unit of Sri Lanka (www.epid.gov.lk)
Weather Data: Department of Meteorology, Sri Lanka (www.meteo.gov.lk)

## 🔍 Methodology
# Data Collection & Integration:
Collected weekly/monthly dengue cases and daily weather data.
Aligned both datasets using district and year as keys.
Normalized time intervals using interpolation techniques.
# Preprocessing:
Handled missing values, applied standardization and min-max normalization.
Feature engineering: moving averages, lag features, and seasonal decomposition.
# Exploratory Data Analysis (EDA):
Correlation heatmaps, trend analysis, and seasonal decomposition to identify relevant predictors.
# Modeling Approaches:
# Initial models: Lasso Regression, Ridge Regression (low performance ~10% accuracy).
Time Series Model: ARIMA (Accuracy: 67.6%)
Machine Learning Model: XGBoost Regression (Accuracy: 95.43%)
# Evaluation Metrics:
Mean Absolute Error (MAE)
Root Mean Squared Error (RMSE)
Cross-Validated MAE

## 🚀 Results
Best Model: XGBoost
District-Level Forecasts for 2025:
Highest risk: Colombo (848 cases), Gampaha (811), Kalutara (453)
Lowest risk: Mullaitivu (9), Mannar (12)


## Key Predictors:

Positive correlation: Temperature, humidity
Negative correlation: Sunshine duration, excessive rainfall

## 📈 Visual Insights
Temporal trends show peak outbreaks in 2017 and 2019.
Forecasts for 2025 indicate an overall decline in cases but continued concern in urban districts.
Heatmaps and trend graphs provided detailed regional insights.

## ✅ Key Findings
Machine learning, particularly XGBoost, outperforms traditional models in outbreak forecasting.
Urban areas with high population density and poor waste management are more vulnerable.
Weather conditions, especially moderate rainfall and high temperature, are strong predictors of dengue outbreaks.

## 💡 Recommendations
Deploy real-time predictive models for early dengue outbreak detection.
Focus public health interventions on high-risk urban districts.
Integrate deep learning and real-time data feeds in future models.
Promote cross-disciplinary collaboration between public health, meteorology, and data science communities.

## 📚 Citation
If you use this work in your research, please cite it as:
Jayawardana, K. S., Hansanee, B. K. M. M., Punchihewa, G. Y., Athukorala, P. A. M. T., & Rathnasekara, C. S. (2025). Pattern Recognition and Predicting Dengue Outbreaks in Sri Lanka Using Machine Learning and Weather Data. General Sir John Kotelawala Defence University.

## 🙏 Acknowledgements
We thank:
The Epidemiology Unit and Department of Meteorology for their datasets.
Our lecturers and the Department of Languages, KDU, for their support and guidance.
