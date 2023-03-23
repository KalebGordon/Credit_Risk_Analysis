# Machine-Learning

## Overview
Using the credit card rist dataset from LendingClub, a peer-to-peer lending services company, we will predict credit risk using the imbalanced-learn and scikit-learn libraries. We are to oversample the data using RandomOverSampler and SMOTE algorithms, then undersample the data using ClusterCentroids. We will then use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Finally, we will compare the two machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. We should then evaluate each models performance. 


## Results
During our analysis using the multiple different machine learning models, we found the following accuracy, precision, and recall scores: 

</div align='center'>
### Naive Random Oversampling
<ul>
  <li>Accuracy: 62.49%</li>
  <img src = 'Images/NRO_Accuracy.JPG'>
  <li>Precision: 99%</li>
  <li>Recall: 65%</li>
  <img src = 'Images/NRO_Report.JPG'>
</ul>


### SMOTE Oversampling
<ul>
  <li>Accuracy: 62.49%</li>
  <img src = 'Images/SMOTE_Accuracy.JPG'>
  <li>Precision: 99%</li>
  <li>Recall: 65%</li>
  <img src = 'Images/SMOTE_Report.JPG'>
</ul>


### Cluster Centroids
<ul>
  <li>Accuracy: 62.49%</li>
  <img src = 'Images/CC_Accuracy.JPG'>
  <li>Precision: 99%</li>
  <li>Recall: 65%</li>
  <img src = 'Images/CC_Report.JPG'>
</ul>


### SMOTEENN
<ul>
  <li>Accuracy: 62.49%</li>
  <img src = 'Images/SMOTEENN_Accuracy.JPG'>
  <li>Precision: 99%</li>
  <li>Recall: 65%</li>
  <img src = 'Images/SMOTEENN_Report.JPG'>
</ul>


### Balanced Random Forest Classifier
<ul>
  <li>Accuracy: 62.49%</li>
  <img src = 'Images/BRFC_Report.JPG'>
  <li>Precision: 99%</li>
  <li>Recall: 65%</li>
  <img src = 'Images/BRFC_Report.JPG'>
</ul>


### Ensemble Classifier
<ul>
  <li>Accuracy: 62.49%</li>
  <img src = 'Images/EEC_Report.JPG'>
  <li>Precision: 99%</li>
  <li>Recall: 65%</li>
  <img src = 'Images/EEC_Report.JPG'>
</ul>
</div>

## Summary


