# Titanic Survival Prediction

## Overview
Solution for the [Titanic Machine Learning Competition](https://www.kaggle.com/competitions/titanic) on Kaggle, scoring 0.77990 on the leaderboard.

## Setup
1. Download competition data from [Kaggle](https://www.kaggle.com/competitions/titanic/data)
2. Place `train.csv` and `test.csv` files in `/kaggle/input/titanic/` directory 
3. Run the notebook `titanic-competition-trying-r.ipynb`

## Approach
- Feature engineering:
 - Converted categorical variables to factors
 - Created age groups
 - Handled missing values
- Models tested:
 - Logistic Regression
 - Random Forest 
 - Decision Tree
- Validation: 5-fold cross validation

## Results
- Final model: Random Forest
- Cross-validation accuracy: 0.804
- Kaggle score: 0.77990
