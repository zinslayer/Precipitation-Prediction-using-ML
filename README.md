# Precipitation-Prediction-using-ML
## Data importing and exploration
 ● PRCP column in the dataframe will be our target feature in this model.Replace all values greater than 0 as 1 (representing precipitation will occur),and values that are equal to 0 representing precipitation will not occur.
 
## Handling class imbalance and missing values
 ● There is an imbalance between examples where precipitation occurs or not therefore overbalance the minority.Check for null values. If any feature contains many null values, we will drop it.
 
## Standardizing data and feature selection 
 ● Feature selection is made using the chi-square test. Then normalize our data.

## Training model using different techniques
  ● Split data into test and train datasets.
  ● We can use logistic regression classifier, decision tree classifier, neural
networks, surface vector machine  etc on training dataset.
  ● Calculated accuracy, precision, recall, F-1 score, and ROC_AUC on the test
dataset and visualize it.
  ● Confusion matrix is plotted.

## Model Comparison
 ● Compared models based on accuracy and ROC_AUC score and visualization is done.
