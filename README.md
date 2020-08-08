# Credit-Card-Fraud-Detection-Kaggle

## Introduction
Ever since starting my journey into data science, I have been thinking about ways to use data science for good while generating value at the same time. Thus, when I came across this data set on Kaggle dealing with credit card fraud detection, I was immediately hooked. The data set has 31 features, 28 of which have been anonymized and are labeled V1 through V28. The remaining three features are the time and the amount of the transaction as well as whether that transaction was fraudulent or not. Before it was uploaded to Kaggle, the anonymized variables had been modified in the form of a PCA (Principal Component Analysis). Furthermore, there were no missing values in the data set. Equipped with this basic description of the data, let’s jump into some exploratory data analysis.

## About Dataset
Dataset for this project can be downloaded from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud)

It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, we cannot provide the original features and more background information about the data. Features V1, V2, … V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.

## Softwares and Dependencies used:
 
  1.**Python3**:[can be downloaded from this link](https://www.python.org)
  
  2.**Anaconda**:[can be downloaded from this link](https://www.anaconda.com)
  
  3.**Pandas**:It's a powerful data analysis and data manipulation tool.
  
  4.**Numpy**:It's a scientific computing library
  
  5.**Seaborn**:Its a Data Visualisation library
 
 ## Results 
 
 precision    recall  f1-score   support

           0       1.00      1.00      1.00     85306
           1       0.66      0.71      0.69       137

    accuracy                           1.00     85443
   macro avg       0.83      0.85      0.84     85443
weighted avg       1.00      1.00      1.00     85443
