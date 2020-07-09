# Unit 11—Risky Business
## Resampling
 - In the first part of notebook, I used the imbalanced learn library to resample the LendingClub data, which was provided in the resources. The resampled data was used to build and evaluate logistic regression classifiers. 

 - Four different algorithms were used in creating models. The first algorithm was oversampling the data using the Naive Random Oversampler; and the second was SMOTE algorithm. Naive Random Oversampler has an accuracy score of 0.677 while SMOTE has an accuracy score of 0.619.

 - The third algorithm was Undersampling by using Cluster Centroids model. It gives an accuracy score of 0.543

- The last algorithm was SMOTEENN, which was used by combining both over- and under-sample. It gives an accuravy score of 0.659. 

- Out of all four models, the Naive Random Oversampler has the highest accuracy score (0.677); The SMOTE model has the best recall score of 0.66; and the Naive Random Oversampler has the best geometric mean score of 0.67. 

## Ensemble
- In the second part of the notebook, two different ensemble classifiers were used to predict loan risk: Balanced Random Forest Classifier and the Easy Ensemble AdaBoost Classifier. 

- The Balanced Radom Forest Classifier model has an accuracy score of 0.764, which is better than the Easy Ensemble AdaBoost model (0.733)

The Easy Ensemble AdaBoost model has a better recall score (1) than the Balanced Random Forest model (0.90).

- In term of geometric mean score, the Balanced Random Forest model has a score of 0.75, which is better then Easy Ensemble AdaBoost's 0.68.

The top three features according to the Balanced Random FOrest model are : total_acc, initial_list_status and pub_rec. 