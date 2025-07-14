# Ensemble Learning and Model Evaluation
Multiple models
solves bias (error in testing data?) and variance (error in training data?)

## Bagging (Bootstrap Aggregation)
- Random Forest 
- multiple models on random subsets of data with replacement (can have repeated data in each model)
- combines result by averaging or voting.
- reduces variance
- runs in parallel

## Boosting
- runs and trains in sequence
- the next model focuses on the error by the previous model.
- reduces bias
- AdaBoost and GradientBoosting
- the algorithms do the weighting like AdaBoost

## Stacking
- combines predictions of models using a meta-model
- the same models for bagging and boosting but for stacking u can use any types => NN, KMeans, Decision trees, SVM, etc.
- a meta model would then combine the predictions from the diff types of models to make the final call
- the predictions are the features for the meta model.
- XGBoost or Logistic regression for the meta model

---

medical and law models need to be interoperable