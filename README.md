# Air-Quality-Index-Prediction
A Machine Learning(ML) project to predict Air Quality Index (AQI) based on pollutant levels using regression models and real-world air pollution data.

# What is AQI?

The **Air Quality Index** (AQI) is a standardized indicator for reporting air quality. 
It is calculated based on the concentrations of major air pollutants such as PM2.5, PM10, NO₂, SO₂, CO, and O₃. AQI values help determine the level of health concern for the general public.

Below is the AQI categorization:

| AQI Level                     | AQI Range |
|------------------------------|------------|
| Good                         | 0 – 50     |
| Moderate                     | 51 – 100   |
| Unhealthy                    | 101 – 150  |
| Unhealthy for Strong People  | 151 – 200  |
| Hazardous                    | 201+       |


### Project Goal

The goal of this project is to develop a **regression model** that can accurately predict AQI values based on pollutant readings. 
This helps in:
 - Early warnings for public health
 - Environmental monitoring
 - Governmental and industrial planning

###  Approach

We preprocess the dataset, perform exploratory analysis, and train a **Random Forest Regressor**. The model's performance is evaluated using common regression metrics, and predictions are visualized for validation.

