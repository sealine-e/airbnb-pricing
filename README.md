# Airbnb Pricing Predictions in Amsterdam
**Project Status: Completed**

## Project Overview
This project explores factors influecing Airbnb pricing in Amsterdam using multiple linear regression. By identifying the most siginificant predictors, such as property features and reviews, this study aims to help hosts in optimizing their listings and aid travellers in finding the best value. 

# Data
The original dataset is from data.world, collected by Philip E. Cannata.
https://data.world/cannata/gaairbnb

## Contributions
- This report was completed by myself, and two other group members.
  
## Research Question
How does age, accomodations, and reviews affect Airbnb prices in Amsterdam?

# Methods
## Tools Used
**R** - tidyverse, ggplot2, dplyr, MASS

## Key Steps
1. **Data Wrangling**: Filtered original dataset for Amsterdam-specific listings and removed incomplete values.
2. **Model Building**:
  - Developed preliminary regression model, fitting predictors chosen from results of previous peer-reviewed studies.
  - Improved model using techniques such as automatic stepwise BIC selection, VIF analysis, variance-stabilizing transformations, and Box-Cox transformations.
3. **Interaction Terms**: Incorporated interaction terms based on previous peer-reviewed studies.
4. **Validation**: Performed ANOVA tests, train-test splits, and Leave-One-Out Cross Validation (LOOCV) to validate the model.

# Final Model
The final model included the predictors property type, number of reviews, review scores, number of people that can be accommodated, and neighbourhood, with an $R^2_{adj}=0.4925$.

## Deliverables
- (Airbnb Pricing Predictions Poster)[]
- (Airbnb Pricing Predictions Report)[]
