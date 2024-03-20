#### Bank-Customer-Churn-Prediction
The task at hand is to predict whether a customer at a bank will close their account or not based on certain given features, as well as the ones you create yourself. The data is obtained from [kaggle](https://www.kaggle.com/competitions/playground-series-s4e1/data).


<hr>

LightGBM, Xgboost and CatBoost with Stratified K-fold were the algorithms used for modelling. Evaluation was done with the Area under Curve(AUC) metric.
The AUC value of the Xgboost model and LightGBM model are 0.85511 and 0.85555, respectively.
The CatBoost model after modelling with Stratified k-fold for 4 folds achieved an average AUC of 0.87545, with the maximum and minimum being 0.87768 and 0.87339, respectively.
The best performing models achived AUC of about 0.89, with one late submission managing to reach 0.905. All these submissions involved the use of features engineering techniques of some sort, hence the accuracy of the three models can be increased by engineering some features.
