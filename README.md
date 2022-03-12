# Cedit_Risk_Analysis

# Overview of the loan prediction risk analysis:
- Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore this analysis will employ different techniques to train and evaluate models with unbalanced classes.using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

- Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, the analysis will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then this will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, this will be compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Finally this will be evaluated the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Results:

- Naive Random Oversampling
- SMOTE Oversampling
- Undersampling
- Combination (Over and Under) Sampling
- Balanced Random Forest Classifier
- Easy Ensemble AdaBoost Classifier

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)

# Summary:

There is a summary of the results (2 pt)

There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
