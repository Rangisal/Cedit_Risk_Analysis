# Cedit_Risk_Analysis

# Overview of the loan prediction risk analysis:
- Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore this analysis will employ different techniques to train and evaluate models with unbalanced classes.using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

- Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, the analysis will oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then this will use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, this will be compared two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Finally this will be evaluated the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Results:

- Naive Random Oversampling - the balanced accuracy score and the precision and recall scores as follows
<img width="960" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/93173498/158004353-bfc83274-8437-4131-b7e2-8fa3994e573b.png">


- SMOTE Oversampling - the balanced accuracy score and the precision and recall scores as follows

<img width="875" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/93173498/158004403-e2ad250e-8879-4be7-ae18-bc254b93be0c.png">


- Undersampling - the balanced accuracy score and the precision and recall scores as follows

<img width="613" alt="Undersampling" src="https://user-images.githubusercontent.com/93173498/158004423-dd963714-c712-48af-9baa-844503a75e07.png">


- Combination (Over and Under) Sampling - the balanced accuracy score and the precision and recall scores as follows

<img width="603" alt="Combination results" src="https://user-images.githubusercontent.com/93173498/158004436-fd2e9587-f49a-4c04-a1ce-b5020559997d.png">

 
- Balanced Random Forest Classifier - the balanced accuracy score and the precision and recall scores as follows

<img width="625" alt="Balanced Random" src="https://user-images.githubusercontent.com/93173498/158004451-e912077b-4543-41db-881f-2ee5772919e5.png">


- Easy Ensemble AdaBoost Classifier - the balanced accuracy score and the precision and recall scores as follows

<img width="613" alt="Easy Ensemble" src="https://user-images.githubusercontent.com/93173498/158004455-ad009c8e-a970-4c67-a8b0-b8995bc3539e.png">


# Summary:

There is a summary of the results (2 pt)

There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
