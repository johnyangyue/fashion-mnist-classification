# Fashion MNIST Classification

## Summary

In this project, we explore the Fashion MNIST data using unsupervised learning and supervised learning techniques. Our high level strategy is to use the insights obtained from the unsupervised learning and single-model supervised learning exercises, combined with hyper-parameter tuning, to come up with an ensemble model that yields high prediction accuracy on the testing set. While the Fashion MNIST is not as complex as some of the state-of-the-art image data sets, it comes with the unique challenge of having some labels looking relatively similar. Our best two-stage ensemble model that incorporates three gradient boosting models (XGBoost, LightGBM, CatBoost) in the first stage and a voting classifier in the second stage achieves an accuracy of 91.71%, beating all of the non-deep learning model based reports we have seen so far.




