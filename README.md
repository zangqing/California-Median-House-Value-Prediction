# California-Median-House-Value-Prediction
Use various machine learning methods to predict California median house value

# Introduction
This project is a classification problem. The dataset we are using is California Housing dataset, which was derived from the 1990 U.S. census, using one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

# File Descriptions
train.csv - the training set \
test.csv - the test set \
sample_submission.csv - a sample submission file in the correct format \
housing.csv - new dataset we merged to add more attributes 

# Attribute Information

## Features
MedInc - median income in block \
HouseAge - median house age in block \
AveRooms - average number of rooms \
AveBedrms - average number of bedrooms \
Population - block population \
AveOccup - average house occupancy \
Latitude - house block latitude \
Longitude - house block longitude \ 
Household - amount of block household (new merged) \
Ocean_proximity - proximity to Pacific ocean (new merged) 

## Label
CatMedHouseValue (Target Variable) - 1: very low, 2: low, 3: medium, 4: high, 5: very high

# Findings
- Applied LDA, SVM, XGBoost, random forest and neural network by using Python, utilized cross-validation to judge different methods 
- Found that random forest and XGBoost had better performance, then used grid search to do hyperparameter tuning for them

