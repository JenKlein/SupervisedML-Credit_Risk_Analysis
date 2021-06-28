# SupervisedML-Credit_Risk_Analysis


## Overview
The purpose of this project was to build a supervised machine learning model to asses credit risk. Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. The imbalanced-learn and scikit-learn libraries were used to build and evaluate the performance of models on whether they should be used to predict credit risk.

### Resources
* Python
* Jupyter notebook
* Imbalanced-learn library
* Scikit-learn library


## Results

### Naive Random Oversampling

![Screen Shot 2021-06-27 at 10 16 33 PM](https://user-images.githubusercontent.com/69849998/123569967-57ea3d80-d795-11eb-834b-969639ec91fc.png)

### SMOTE Oversampling

![Screen Shot 2021-06-27 at 10 17 11 PM](https://user-images.githubusercontent.com/69849998/123570054-7a7c5680-d795-11eb-900a-ce81317efb49.png)

### Undersampling

![Screen Shot 2021-06-27 at 10 17 11 PM](https://user-images.githubusercontent.com/69849998/123570167-a7c90480-d795-11eb-9605-1c9b86795667.png)

### Combination (Over and Under) Sampling

![Screen Shot 2021-06-27 at 10 19 44 PM](https://user-images.githubusercontent.com/69849998/123570228-c929f080-d795-11eb-9387-d63ce3322e05.png)

### Balanced Random Forest Classifier

![Screen Shot 2021-06-27 at 10 21 26 PM](https://user-images.githubusercontent.com/69849998/123570348-055d5100-d796-11eb-9c70-649ede963480.png)

### Easy Ensemble AdaBoost Classifier

![Screen Shot 2021-06-27 at 10 20 11 PM](https://user-images.githubusercontent.com/69849998/123570272-d9da6680-d795-11eb-9280-84cd331d7e51.png)


## Summary
Of all the models, the Easy Ensemble AdaBoost Classifier had the highest balanced accuracy score at 73%, meaning that 73% of the time the model predicts credit risk accurately. The Imbalanced Classification Reports for the Easy Ensemble AdaBoost, as well at the Balanced Random Forest Classifier demonstrate high precision scores at 0.99, high recall scores at 0.97. If it’s necessary to use one of the 6 models discussed, it would be advisable to use the Easy Ensemble AdaBoost Classifier model to predict credit risk because of it has the highest accuracy, precision and recall. However, 73% accuracy means that 27% of the time, the model incorrectly predicts credit risk, so it’s recommended to use another model different from those discussed that has a higher accuracy score. 
