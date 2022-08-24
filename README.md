# Credit_Risk_Analysis


### Goal
 
  Enable a data based decisions on whether to approve an individual for a line of credit we utilized numerous supervised machine learning models. All the dataset for the credit card info was provided by Lending Club.
  After futher accessment from many different Machine Learning models, we learned that this data is unbalanced. Therefore, we did some balancing by utilizing multiple algorithms to resample the data (all from Scikit-learn library).
  
  
### The results:

##### Random Over Sampler
Precision: high risk 0.01 / low risk 0.99
Recall: high risk 0.74 / low risk 0.57

##### SMOTE
Precision: high risk 0.01 / low risk 0.99
Recall: high risk 0.52 / low risk 0.69

##### Cluster Centroids
Precision: high risk 0.01 / low risk 0.99
Recall: high risk 0.48 / low risk 0.44

##### SMOTEENN
Precision: high risk 0.01 / low risk 0.99
Recall: high risk 0.74 / low risk 0.57

##### Balanced Random Forest Classifier
Precision: high risk 0.03 / low risk 1.00
Recall: high risk 0.70 / low risk 0.87

##### Easy Ensemble Classifier
Precision: high risk 0.09 / low risk 1.00
Recall: high risk 0.92 / low risk 0.94

