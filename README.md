# PGA-Tour-Prediction-Modeling

1. Data Imports:
  Import the data from the DataGolf.com API. Processes the data from JSON into pandas then eventually saves as CSV. Should work for all future updates to the dataset. Notes on the dataset can be found here: https://datagolf.com/api-access. 
NOTE: for this file to work, need a datagolf.com subscription. 
  
2. Data Processing and Factor Creation:
  Process the data (clean, EDA, ext.) and then create basic factors for the linear model. Need round data from previous document for this to work. Creates two strokes gained historical metrics for all players, one short term and one long term. Also creates some event strength metrics (needed for testing against strokes gained), creates/fixes some course information. 
  
3. Linear Model Creation - Baseline Prediction:
  Modeling processing behind the linear model. Iterative process, saves the base linear regression model. The model itself is not very predictive (as measured by R-squared). Goes into how it can be leveraged, why low R-squared may not be bad at a round level. 
  
4. Model Creation - Residuals and Course Fit:
  Use the baseline model to predict for the future - use the residuals to create course fit ideas. Go over how to integrate the course fit idea into the baseline model - also how it can be improved. 
