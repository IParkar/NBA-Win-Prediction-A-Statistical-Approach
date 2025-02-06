# NBA-Win-Prediction-A-Statistical-Approach
NBA Win Prediction
This repository contains Python code for predicting NBA team win percentages using a statistical approach.

# Dataset
Data Sources:

Basketball-Reference.com:
Scraped data for team standings (Eastern and Western Conference) and per-game statistics.
Team_Player_Stats_Train_2022_23.xlsx:
Contains additional player-level statistics for the 2022-2023 season.
Team_Player_Stats_Test_2023_24.xlsx:
Contains additional player-level statistics for the 2023-2024 season.

# Data Cleaning:

Merged data from different sources (standings, per-game stats, player stats).
Converted relevant columns to numeric data types.
Handled missing values and invalid data.
Exploratory Data Analysis (EDA)

# Data Visualization:
Created histograms to analyze the distribution of player age and height.
Generated bar plots to visualize the relationship between win percentage and key variables (e.g., Field Goals, Turnovers, Fouls).
Calculated and visualized the correlation matrix of relevant variables.
Created pair plots to explore pairwise relationships between variables.

# Model Building
Linear Regression Models:
Built and trained multiple linear regression models using statsmodels library.
Tested different combinations of predictor variables (e.g., Field Goals, Turnovers, Fouls, Height, Experience).
Evaluated model performance using metrics like Mean Squared Error (MSE).

# Results

Model Selection:
The best-performing model included variables such as Field Goals, Free Throws, Turnovers, Steals, Weight, and Experience.

# Future Work

Improve Data Collection:
Incorporate more comprehensive player-level statistics.
Explore alternative data sources (e.g., player salaries, injury data).

Enhance Model Complexity:
Experiment with more sophisticated models, such as:
Regularization techniques (e.g., Ridge, Lasso)
Tree-based models (e.g., Random Forest, Gradient Boosting)
Neural networks

Feature Engineering:
Create new features based on existing data (e.g., team pace, offensive/defensive efficiency).

