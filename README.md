# Credit_Risk_Analysis
## Overview of the loan prediction risk analysis:
The objective of this project is to analyze the accuracy of different models and decide which one will provide the most accurate prediction of credit risk.

## Results:

### Naive Random Oversampling
![Slide1](https://user-images.githubusercontent.com/82242081/137576539-339fe594-ff98-4001-bc4f-84583cac69df.PNG)
- Balanced Accuracy Score: 64.737%
- Precision High_Risk: 1%
- Precision Low_Risk: 100%
- Recall High_Risk: 69%
- Recall Low_Risk: 60%
### SMOTE Oversamplling
![Slide2](https://user-images.githubusercontent.com/82242081/137576557-8322c86f-e5e6-469d-93a4-f6cdf33d93b0.PNG)
- Balanced Accuracy Score: 66.216%
- Precision High_Risk: 1%
- Precision Low_Risk: 100%
- Recall High_Risk: 63%
- Recall Low_Risk: 69%
### Cluster Centroid Undersampling
![Slide3](https://user-images.githubusercontent.com/82242081/137576563-c4278f3f-eb7e-4434-9ad5-5efd91936b43.PNG)
- Balanced Accuracy Score: 58.023%
- Precision High_Risk: 1%
- Precision Low_Risk: 100%
- Recall High_Risk: 58%
- Recall Low_Risk: 58%
### SMOTEENN COMBINATION SAMPLING
![Slide4](https://user-images.githubusercontent.com/82242081/137576567-27cf1f43-574a-4cd3-8d0e-5b6227d5ea9f.PNG)
- Balanced Accuracy Score: 67.754%
- Precision High_Risk: 1%
- Precision Low_Risk: 100%
- Recall High_Risk: 78%
- Recall Low_Risk: 57%
### Balanced Random Forest Classifier
![Slide5](https://user-images.githubusercontent.com/82242081/137576568-a3b840cd-39fb-4a40-b773-49c97fb92a99.PNG)
- Balanced Accuracy Score: 78.855%
- Precision High_Risk: 3%
- Precision Low_Risk: 100%
- Recall High_Risk: 70%
- Recall Low_Risk: 87%
### Easy Ensemble AdaBoost Classifier
![Slide6](https://user-images.githubusercontent.com/82242081/137576570-b2321fdd-eadb-4c50-8285-57ebd6cb3875.PNG)
- Balanced Accuracy Score: 93.166%
- Precision High_Risk: 9%
- Precision Low_Risk: 100%
- Recall High_Risk: 92%
- Recall Low_Risk: 94%
## Summary:
Out of all the models, Easy Ensemble AdaBoost Classifier model provides the highest accuracy rate.
