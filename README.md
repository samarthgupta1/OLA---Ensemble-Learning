# OLA---Ensemble-Learning
We are focused on driver team attrition. We are provided with the monthly information for a segment of drivers for 2019 and 2020 and tasked to predict whether a driver will be leaving the company or not

Imported the dataset and do usual exploratory analysis steps like checking the structure & characteristics of the dataset.

Converted date-like features to their respective data type

Checked for missing values and Prepared data for KNN Imputation

Aggregated data in order to remove multiple occurrences of same driver data You can start from storing unique Driver IDs in an empty dataframe and then bring all the features at same level (Groupby Driver ID)

Feature Engineering Steps:
Created a column which tells whether the quarterly rating has increased for that driver - for those whose quarterly rating has increased we assigned the value 1
Targeted variable creation: Create a column called target which tells whether the driver has left the company- driver whose last working day is present assigned the value 1
Created a column which tells whether the monthly income has increased for that driver - for those whose monthly income has increased we assigned the value 1


Checked correlation among independent variables and how they interact with each other

One hot encoding of the categorical variable

Class Imbalance Treatment

Standardization of training data

Used Ensemble learning - Bagging, Boosting methods with some hyper-parameter tuning

Results Evaluation: Classification Report, ROC AUC curve
