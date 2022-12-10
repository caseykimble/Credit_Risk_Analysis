# Credit Risk Analysis

### Overview

The purpose of this analysis was to apply machine learning models to evaluate credit card risk.

Using a credit card credit dataset from LendingClub, I used several machine learning methods to review whether or not they should be used to predict credit risk. 

The following methods were used:
* oversampling with RandomOverSampler and SMOTE algorithms
* undersampling with ClusterCentroids algorithm
* combination over- and undersampling using SMOTEENN algorithm
* models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier

Following these steps, I will evaluate the performance of these models and make a written recommendation on their predictability for credit risk.



### Results

#### Naive Random Oversampler - 
  Naive Random Oversampling had an accuracy of 67%, recall of 68% on high-risk and 66% on low-risk, with a sensitivity of 1%.
<img width="820" alt="NaiveRandomOversampler" src="https://user-images.githubusercontent.com/105175961/206876331-cac3b648-5ede-4b51-8051-9fc6b49f5956.png">

#### SMOTE Oversampler
  SMOTE Oversampling showed accuracy of 64.1%, recall of 68% on high-risk and 60% on low-risk, with a sensitivity of 1%.
<img width="802" alt="SMOTE Oversampler" src="https://user-images.githubusercontent.com/105175961/206876368-9dd7ddc9-0033-4ad2-bc1a-94e47300bbb9.png">

#### Cluster Centroids Undersampler
  Cluster Centroids Undersampling had an accuracy of 54.3%, recall of 68% on high-risk and 40% on low-risk, with a sensitivity of 1%.
<img width="803" alt="ClusterCentroidUndersampler" src="https://user-images.githubusercontent.com/105175961/206876393-9e5b9666-d63b-4c20-b735-76ed7923eeb7.png">

#### SMOTEENN Over- and Undersampler
  SMOTEENN Over- and Undersampling had an accuracy of 64.4%, recall of 76% on high-risk and 52% on low-risk, with a sensitivity of 1%.
<img width="794" alt="SMOTEENNOverUnder" src="https://user-images.githubusercontent.com/105175961/206876447-62bbf1a0-af15-4718-9c39-02da9dfef72b.png">

#### Balanced Random Forest Classifier
  Balanced Random Forest Classifier had an accuracy of 78.9%, recall of 70% on high-risk and 87% on low-risk, with a sensitivity of 3%.
<img width="805" alt="BalancedRandomForest" src="https://user-images.githubusercontent.com/105175961/206876487-fcf9e2ee-0df8-416f-b7d0-09f7d044f20b.png">

#### EasyEnsemble Classifier
  EasyEnsemble Classifier had an accuracy of 93.2%, recall of 92% on high-risk and 94% on low-risk, with a sensitivity of 9%.
<img width="801" alt="EasyEnsemble" src="https://user-images.githubusercontent.com/105175961/206876509-5ca88f6b-4761-431a-a072-06e8d5aed832.png">



### Summary

I would recommend using our EasyEnsemble Classifier model, which has the highest accuracy at 93.2%, and a better low-risk recall rate of 94% and high-risk recall rate of 92%. It also has a sensitivity of 9% which is much higher than any other model. 




