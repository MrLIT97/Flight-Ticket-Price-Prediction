# Flight-Ticket-Price-Prediction
Introduction: This project focuses on the application of python tools to analyze the different factors affecting ticket price variation in the given dataset. Question were answered through EDA and a viable predicion model was developed. This is aimed at guiding indivuals looking to book a flight in the future on decision making and could also help airlines improve on their services through an "Ease My Trip" website.

## Dataset Description:
The dataset was collected from kaggle (https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction). It is a mixture of continuous and discrete variables with 300,153 observations, 11 features and 1 target that are outlined as follows:

airline - the airline providing the service

flight - the unique identity for each flight booking

source_city - where the trip starts

depature_time - time flight starts

stops - number of stops during flight

arrival_time - time flight ends

destination_city - where trip ends

class - social class (Business or Economy)

duration - time spent on the trip

days_left - days left before departure

price - Ticket price

## Expertise Demonstrated:

- Data Cleaning and Wrangling
- Exploration Data Analysis
- Data manipulation
- Machine Learning modeling and Optimization

## Tool used:
Python
  
## Machine Learning methods:

1. Column Transformation for feature scaling with One Hot Encoding for categorical variables, Ordinal Encoding for ordical categorical variables and MinMax scaling on continuous variables.
2. Target Transformation with Quantile and Log Transformation on target variable to normalized skewness
3. Model building with Pipeline
4. Optimization approach:
    * Feature Selection using K-Best and Mutual Info Regression
    * Model comparison

## Models Selected: (Dealing with Regression since target variable is continuous)
1. Linear Regressor
2. Random Forest Regressor
3. Gradient Boosting Regressor

## Evaluation Metrics:
1. Mean Squared Error
2. Root Mean Squared Error
3. Mean Absolute Error
4. Mean Absolute Percentage Error
5. R2 Score

## Result: 
Random Fores Regressor performs the best with least error and thus chosen as the viable model.
