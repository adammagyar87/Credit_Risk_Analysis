# Credit_Risk_Analysis

## Our assignment was to use machine learning models via python to review credit applications and determine risk. We did the following:

- Use Resampling Models to Predict Credit Risk
- Use the SMOTEENN Algorithm to Predict Credit Risk
- Use Ensemble Classifiers to Predict Credit Risk

## Deliverable 1: 

We created and compared three machine learning models. We used two oversampling algorithms, RandomOverSampler and SMOTE. We then used an undersampling algorithms, ClusterCentroids. The results for each are found below:

###  RandomOverSampler
![image](https://user-images.githubusercontent.com/87042597/150717974-6cef8555-a877-47ba-8d9f-f362c6120f49.png)


### SMOTE
![image](https://user-images.githubusercontent.com/87042597/150718012-05f61bb7-d6c8-4cf8-97ef-df41191809f2.png)

### ClusterCentroids
![image](https://user-images.githubusercontent.com/87042597/150718046-1dc3f8ac-8544-4bc2-bcb7-658336b3ab11.png)

## Deliverable 2:

We utilized the SMOTEENN algorithm which is a combination of both over and undersampling as another comparison. The results from this model are seen below:
### SMOTEENN
![image](https://user-images.githubusercontent.com/87042597/150718398-7d21de19-05d2-4f52-9110-5505e07fd144.png)


## Deliverable 3: 

We compared two ensemble algorithms to determine which would result in the best performance. The two models used were a Balanced Random Forest Classifier and an Easy Ensemble AdaBoost classifier. The results are seen below:

### Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/87042597/150718613-0a8d8476-a329-4458-9b8c-3efc407edf2d.png)

### Easy Ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/87042597/150718641-691a8b12-7290-4e4d-86c1-c64cc26aa476.png)

### Deliverable 4: Summary

Looking at the results, we see that the ensemble alorithms drastically out performed the models from Deliverable 1 and 2 in regards to accuracy. The first models we used had the following results:

#### RandomOverSampler 
- Accuracy  65.2%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 62%
- Recall Low Risk: 68%

#### SMOTE 
- Accuracy  62.4%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 59%
- Recall Low Risk: 66%

#### ClusterCentroids
- Accuracy  51.6%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 60%
- Recall Low Risk: 43%

#### SMOTEENN
- Accuracy  62.2%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 71%
- Recall Low Risk: 53%

#### Balanced Random Forest Classifier
- Accuracy  78.8%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 67%
- Recall Low Risk: 91%

#### Easy Ensemble AdaBoost Classifier
- Accuracy  92.5%
- Precision High Risk: 7%
- Precision Low Risk: 100%
- Recall High Risk: 91%
- Recall Low Risk: 94%

Factoring in all of the info from the different models, the Easy Ensemble AdaBoost Classifier performed the best. It had a very high accuracy rate of 92.5% but the recall rate of 91% means that there will be a relativley high amount of low risk applications flagged as high risk. This indicates that there would be risk in using this model, but it did perform better than the others in the evaluation. 
