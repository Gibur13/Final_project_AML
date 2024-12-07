# Air Quality Prediction Project

## Overview
This project aims to develop a predictive model for urban air quality, focusing on forecasting key indicators such as PM2.5, PM10, and NO2 levels. By leveraging historical air quality data, meteorological conditions, and other environmental variables, the model provides early warnings of poor air quality to support public health initiatives and help individuals adjust their activities.

## Team Members
- Bora Bulut  
- Yuval Steimberg  
- Aashish Khubchandani  

## Objective
To create an accurate and actionable forecasting model for air quality that:
- Predicts pollutant-specific Air Quality Index (AQI) levels.
- Provides granular insights into pollution sources and impacts.
- Supports public health measures through early warnings.

## Dataset
We are using the **U.S. Pollution Data (2000-2023)** dataset available on Kaggle:
[U.S. Pollution Data](https://www.kaggle.com/datasets/guslovesmath/us-pollution-data-200-to-2022/data)

### Data Usage
- **Training (2000-2018)**: Model training phase.
- **Evaluation (2019-2020)**: Cross-validation phase.
- **Testing (2021-2023)**: Model testing phase.

## Methodology
Our approach involves:
1. **Classification System**: Categorizing air quality changes into ranges (e.g., ±0–5%, ±5–10%).
2. **Models**: Comparing decision trees, random forests, and k-nearest neighbors (KNN).
3. **City Focus**: Initial predictions for New York City (NYC), with potential extensions to other cities.

### Key Features
- **Composite AQI Calculation**: Reflects the maximum AQI values of pollutants (O3, CO, SO2, NO2).
- **Granular Forecasts**: Individual pollutant-specific AQI values for deeper analysis.
- **Comparative Evaluation**: Metrics such as RMSE and accuracy for model assessment.
- **Comprehensive Results**: Visualized through graphs and documented metrics.

## Previous Work
Our work builds on the research from:
[Prediction of Air Quality Index Using Machine Learning Techniques: A Comparative Analysis](https://onlinelibrary.wiley.com/doi/10.1155/2023/4916267)

### Key Findings from Previous Work:
- Regression models such as Support Vector Regression (SVR), Random Forest Regression (RFR), and CatBoost Regression (CR) were applied to AQI data from Indian cities.
- Random Forest showed superior performance in most scenarios.

## Future Work
- Extend predictions to other cities beyond NYC.
- Incorporate additional variables such as industrial activity and traffic data.
- Explore advanced machine learning models, including ensemble methods.



## Acknowledgments
We thank the Kaggle community for the dataset and the research community for foundational work on air quality prediction.
