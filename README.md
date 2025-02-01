Titanic Survival Prediction
Solution for the Titanic Machine Learning Competition on Kaggle, scoring 0.77990.
Setup

Download competition data from Kaggle
Place train.csv and test.csv files in /kaggle/input/titanic/ directory
Run the notebook titanic-competition-trying-r.ipynb

Approach

Feature engineering:

Converted categorical variables to factors
Created age groups
Handled missing values


Models tested:

Logistic Regression
Random Forest
Decision Tree


Validation: 5-fold cross validation

Results

Final model: Random Forest
Cross-validation accuracy: 0.804
Kaggle score: 0.77990

