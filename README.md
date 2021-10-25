# Credit Risk Analysis
## Overview of the analysis: 
#### The purpose of this analysis is to work with machine learning models and test them to see which one(s) work very well to predict credit card risk. The credit card credit dataset will be based from the LendingClub, a peer-to-peer lending services company.

## Results of the Machine Learning Models:
### Naive Random Oversampling:
- Its balanced accuracy score: 64%
- High Risk Precision is of 1% and High Rish Recall score is 66%.
<img width="711" alt="Naive Random Oversampling" src="https://user-images.githubusercontent.com/86431959/138628690-fcbf9df1-91b7-4198-9c0b-64bd9195deb6.png">


### SMOTE: 
- Its balanced accuracy score: 66%
- High Risk Precision is of 1% and High Rish Recall score is 62%.
<img width="711" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/86431959/138628812-be957489-b155-4ee6-a9e8-314467189f07.png">


### Cluster Centroids:
- Its balanced accuracy score: 66%
- High Risk Precision is of 1% and High Rish Recall score is 69%.
<img width="708" alt="Cluster Centroids" src="https://user-images.githubusercontent.com/86431959/138628926-8172a367-7098-408f-aea7-83cb04a7a708.png">


### SMOTEENN:
- Its balanced accuracy score: 54%
- High Risk Precision is of 1% and High Rish Recall score is 69%.
<img width="719" alt="SMOTEENN" src="https://user-images.githubusercontent.com/86431959/138629047-b59a9f0d-e4d0-44db-8fc2-4332c525888c.png">


### Balanced Random Forest Classifier:
- Its balanced accuracy score: 77%
- High Risk Precision is of 3% and High Rish Recall score is 67%.
<img width="711" alt="Balanced Random Forest Classifier" src="https://user-images.githubusercontent.com/86431959/138629148-66cfc912-2622-487c-b74d-82729f02b0bc.png">
 
 
### Easy Ensemble AdaBoost Classifier:
- Its balanced accuracy score: 93%
- High Risk Precision is of 9% and High Rish Recall score is 92%.
<img width="705" alt="Easy Ensemble AdaBoost Classifier" src="https://user-images.githubusercontent.com/86431959/138629316-6c485ba4-17a6-49a4-a035-d0ea8c093be5.png">


## Summary: 
#### In summary, all six models were not very accurate when determining the credit card risk. The machine learning model that had the most promise was the Easy Ensemble AdaBoost Classifier. In comparison to the other five models this model had the highest score in balanced accuracy which was 93%. When comparing its high risk precision and recall scores with the other five models it too had the highest scores. I would recommend to use the Easy Ensemble AdaBoost Classifier, but I would definitely work on making improvements on the model to make it more precise when getting the results.
