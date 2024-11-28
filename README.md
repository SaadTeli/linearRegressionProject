# linearRegressionProject

# Bike Sharing Demand Prediction

## Project Overview
This project aims to predict the demand for shared bikes using a multiple linear regression model. The analysis identifies key factors influencing bike demand and helps in making data-driven business decisions.

## Dataset
The dataset contains information on daily bike rentals, weather conditions, and temporal variables. Data was preprocessed and cleaned to ensure high quality for modeling.

## Preprocessing
- Converted categorical variables to string labels.
- Created dummy variables for categorical features.
- Dropped unnecessary columns.
- Handled missing values.

## Exploratory Data Analysis (EDA)
- Visualized the distribution of bike rentals.
- Examined relationships between numerical features and bike demand.
- Analyzed the impact of categorical features on bike demand.

## Model Building
- Built and trained a multiple linear regression model.
- Evaluated the model using R-squared and RMSE metrics for both training and testing sets.

## Findings
- Significant predictors include year, season, weather situation, and holidays.
- Temperature has the highest correlation with bike demand.
- Adverse weather conditions and holidays negatively impact bike demand.

## Results
- **Training R-squared**: 0.8179
- **Training RMSE**: 833.67
- **Testing R-squared**: 0.8488
- **Testing RMSE**: 719.29

## Conclusion
The model effectively predicts bike demand and provides valuable insights for business strategy optimization. Key factors such as weather conditions, seasons, and holidays play a significant role in determining bike rental demand.

## Files
- `Bike_Sharing_Demand_Prediction.ipynb`: Jupyter notebook with the complete analysis.
- `Subjective_Questions.pdf`: Answers to the subjective questions.
- `README.md`: This file summarizing the project.
