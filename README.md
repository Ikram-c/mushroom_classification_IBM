# Mushroom Supervised Classification Project (part of IBM ML certification)


## Overview of project
The aim of the project was to use supervised classification models to predict whether a mushroom was poisonous to eat or not (***Binary classification***). The data was sourced from the Mushroom Classification dataset on kaggle (https://www.kaggle.com/datasets/uciml/mushroom-classification)

Data was imported from a CSV into a Pandas dataframe and EDA was conducted to find nulls, the distribution (using a histogram) and plotting a Seaborn correlation Matrix. *** Cardinality*** was also checked to help assess which features to use for the model.

The categorical data was encoded using Sklearn's LabelEncoder and a test train split was used to split the data into training and testing sets.

The following Supervised classification models were then used (it should be noted that more models were planned to be used and will be in future updates):

- ***Logistic Regression***
- ***KNeighborsClassifier***
- ***DecisionTreeClassifier***

The models were assessed using Confusion matrices and F1 scores.

![Classification plot confusion matrix](https://user-images.githubusercontent.com/68299933/215765549-d1a99592-e2dc-4579-acb6-9896819eda67.jpg)

(Sample of confusion matrix plot of logistic regression classification)


See Notebook for detailed breakdown.

