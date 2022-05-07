# Fraud_Prediction
An individual project during college as Data Science course requirements

Data source: https://www.kaggle.com/ntnu-testimon/paysim1


**Conclusions from this analysis**:

1. Imbalanced data causes prediction inaccuracies, as well as data reading errors. To fix this, use **randomundersample** as pipeline 

2. **Randomundersample** equates the sample group with fewer (minority) with more (majority)

3. Based on the Confusion Matrix Test: The more accurate model used is logistic regression, because the accuracy rate is higher, the number of False Positives and False Negatives is less than the Random Forest model.

4. Based on ROC-AUC Model: The more accurate model used is logistic regression, because the AUC value is higher than the Random Forest model
