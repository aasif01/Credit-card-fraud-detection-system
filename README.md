# Credit-card-fraud-detection-system
 The project is based on Predicting Unemployment Rate Data using Machine Learning .Find the relevant data from the sources like: Kaggle, UCI etc.
dats is a CSV file, contains 31 features, the last feature is used to classify the transaction whether it is a fraud or not.

Information about data set
* The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
* It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues original features are not provided and more background information about the data is also not present. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise.
* Given the class imbalance ratio, we recommend measuring the accuracy using the Area Under the Precision-Recall Curve (AUPRC). Confusion matrix accuracy is not meaningful for unbalanced classification.


##Steps followed to complete this project:
*	  Download the data set in .xlsx format from ⦁	www.kaggle.com
*   Import the data from the data set
*   Determine number of fraud cases in dataset
*   Plot the Correlation Matrix
*   The correlation matrix graphically gives us an idea of how features correlate with each other and can help us predict what are the       features that are most relevant for the prediction.
*   Separate the X and the Y values and then we 
*   Divide the data into inputs parameters and outputs value format
*   We will be divide the dataset into two main groups. One for training the model and the other for Testing our trained model’s             performance.
*  and for accuracy check we have implemented random forest classifier model and at last we print confusion matrix.
    
##output
    The model used is Random Forest classifier
*  The accuracy is  0.9995611109160493
*  The precision is 0.9866666666666667
*  The recall is 0.7551020408163265
*  The F1-Score is 0.8554913294797689
*  The Matthews correlation coefficient is0.8629589216367891
