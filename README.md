# Credit_Risk_Analysis
Supervised Machine Learning and Credit Risk 
## Overview
The purpose of this project was to develop a supervised machine learning model that could effectively predict credit risk. Inorder to do this the following procedure was used:
* Naive Random Oversampling using RandomOversampler
* SMOTE Oversampling
* Undersampling using Cluster Centroid 
* Combination (Over and Under) Sampling using SMOTEENN
* Balanced Random Forest Classifying
* Easy Ensemble Classifying

For each of these procedure the data was split into training and testing datasets. For each results accuracy scores, confusion matries, and classification reports were created.   
## Results
#### Naive Random Oversampling using RandomOversampler
![image](https://user-images.githubusercontent.com/93439516/157512385-5da8f402-528a-4f88-878b-6c73253f7cc1.png)
* Accuracy Score: 65%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 68%
* Recall Low Risk: 68%

#### SMOTE Oversampling
![image](https://user-images.githubusercontent.com/93439516/157513022-0272fc65-bb20-49a8-a13a-6d712e1e419c.png)
* Accuracy Score: 63%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 59%
* Recall Low Risk: 66%

#### Undersampling using Cluster Centroid 
![image](https://user-images.githubusercontent.com/93439516/157513134-999f13aa-68eb-41fd-911a-d0b9eee94a91.png)
* Accuracy Score: 52%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 60%
* Recall Low Risk: 43%

#### Combination (Over and Under) Sampling using SMOTEENN
![image](https://user-images.githubusercontent.com/93439516/157513322-8c5bbdeb-0731-4778-a62b-16ec3bdf2f53.png)
* Accuracy Score: 62%
* Precision High Risk: 1%
* Precision Low Risk: 100%
* Recall High Risk: 71%
* Recall Low Risk: 53%

#### Balanced Random Forest Classifying
![image](https://user-images.githubusercontent.com/93439516/157513501-8ca2a77d-2534-4c94-b95e-40cc7c7b5399.png)
* Accuracy Score: 79%
* Precision High Risk: 4%
* Precision Low Risk: 100%
* Recall High Risk: 67%
* Recall Low Risk: 91%

#### Easy Ensemble Classifying
![image](https://user-images.githubusercontent.com/93439516/157513608-2f62f8d7-0570-4709-bcdf-4b9faee0fe75.png)
* Accuracy Score: 93%
* Precision High Risk: 7%
* Precision Low Risk: 100%
* Recall High Risk: 91%
* Recall Low Risk: 94%

## Summary
All of the credit risk analysis models have low precision in assessing whether a credit risk is high. The Ensemble models resulted in significant improvements, particularly in the sensitivity of high-risk credits. With a recall of 91 percent, the EasyEnsembleClassifier model can detect almost all high-risk credit. On the other hand, because of the low precision, many low-risk credits are still misclassified as high-risk, putting the bank's credit strategy at risk and causing it to miss out on income prospects. As a result, I would advise the bank against using any of these algorithms to anticipate credit risk.

## Resources 
* Data: LoanStats_2019Q1.csv.
* Software: Jupyter Notebook 
