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

#### Naive Random Oversampler
<img width="820" alt="NaiveRandomOversampler" src="https://user-images.githubusercontent.com/105175961/206876331-cac3b648-5ede-4b51-8051-9fc6b49f5956.png">

#### SMOTE Oversampler
<img width="802" alt="SMOTE Oversampler" src="https://user-images.githubusercontent.com/105175961/206876368-9dd7ddc9-0033-4ad2-bc1a-94e47300bbb9.png">

#### Cluster Centroids Undersampler
<img width="803" alt="ClusterCentroidUndersampler" src="https://user-images.githubusercontent.com/105175961/206876393-9e5b9666-d63b-4c20-b735-76ed7923eeb7.png">

#### SMOTEENN Over- and Undersampler
<img width="794" alt="SMOTEENNOverUnder" src="https://user-images.githubusercontent.com/105175961/206876447-62bbf1a0-af15-4718-9c39-02da9dfef72b.png">

#### Balanced Random Forest Classifier
<img width="805" alt="BalancedRandomForest" src="https://user-images.githubusercontent.com/105175961/206876487-fcf9e2ee-0df8-416f-b7d0-09f7d044f20b.png">

#### EasyEnsemble Classifier
<img width="801" alt="EasyEnsemble" src="https://user-images.githubusercontent.com/105175961/206876509-5ca88f6b-4761-431a-a072-06e8d5aed832.png">





BalancedRandomForest, EasyEnsemble

### Summary





Deliverable 4: Written Report on the Credit Risk Analysis
For this deliverable, you’ll write a brief summary and analysis of the performance of all the machine learning models used in this Challenge.

The report should contain the following:

Overview of the analysis: Explain the purpose of this analysis.

Results: Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.



Deliverable 4: Written Report on the Credit Risk Analysis (30 points)
Structure, Organization, and Formatting
The written analysis has the following structure, organization, and formatting:

There is a title, and there are multiple sections (2 pt)
Each section has a heading and subheading (2 pt)
Links to images are working, and code is formatted and displayed correctly (2 pt).
Analysis
The written analysis has the following:

Overview of the loan prediction risk analysis:

The purpose of this analysis is well defined (4 pt)
Results:

There is a bulleted list that describes the balanced accuracy score and the precision and recall scores of all six machine learning models (15 pt)
Summary:

There is a summary of the results (2 pt)
There is a recommendation on which model to use, or there is no recommendation with a justification (3 pt)
