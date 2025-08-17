# Air_Qualty_Index
# Introduction
The Air Quality Index (AQI) dataset provides a detailed view of air pollution levels across various cities over time. It captures the concentration of major air pollutants and combines them into a single metric—the AQI—which reflects the overall air quality. Monitoring these pollutants is essential for understanding environmental health, guiding public policy, and informing individuals about potential health risks.

# Problem Statement
Air pollution poses a significant threat to public health, especially in urban areas where industrial activities and vehicle emissions are high. Understanding the patterns and contributors to poor air quality can help in developing effective environmental policies and public health advisories. This project aims to analyze and model air quality data collected from multiple cities over time. The primary goal is to identify key factors contributing to poor air quality and develop predictive models to forecast the Air Quality Index (AQI) based on pollutant levels. This will enable stakeholders to take proactive measures to reduce pollution and protect public health.

# Dataset Information
## 📑 Dataset Information

## 📑 Dataset Information

| Column Name     | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| id              | Unique identifier for each record                                           |
| country         | Name of the country where the pollution data was recorded                   |
| state           | State or province within the country                                        |
| city            | City in which the monitoring station is located                             |
| station         | Specific air quality monitoring station name or code                        |
| pollutant_id    | Identifier/code of the measured pollutant (e.g., PM2.5, PM10, NO2, SO2, O3) |
| last_update     | Date and time of the most recent measurement                                |
| pollutant_min   | Minimum recorded concentration of the pollutant                             |
| pollutant_max   | Maximum recorded concentration of the pollutant                             |
| pollutant_avg   | Average concentration of the pollutant                                      |

# Libraries
* pandas
* numpy
* matplotlib / seaborn
* ydata_profiling
* sklearn

# Algorithms
* LabelEncoder, OneHotEncoder
* RobustScaler, MinMaxScaler, StandardScaler
* train_test_split
* LinearRegression
* r2_score
* LogisticRegression
* DecisionTreeClassifier
* RandomForestClassifier
