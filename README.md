#### Bank-Customer-Churn-Prediction
The task at hand is to predict whether a customer at a bank will close their account or not based on certain given features, as well as the ones you create yourself.

<hr>

LightGBM, Xgboost and CatBoost with Stratified K-fold were the algorithms used for modelling. Evaluation was done with the Area under Curve(AUC) metric.
The AUC value of the Xgboost model and LightGBM model are 0.85511 and 0.85555, respectively.
The CatBoost model after modelling with Stratified k-fold for 4 folds achieved an average AUC of 0.87545, with the maximum and minimum being 0.87768 and 0.87339, respectively.
