# ML_Telecom_Churn_Predict_Modeling
Predicting customer churning to different service provider based on the different customer parameters - recharge amount, data/voice/roaming usage

Customer data collected months: June, July, August and September

Based on the first 3 months (June, July, Auguest), predicting Customer to churn out to different service provider in September month.

Model highlights:
=================
* Feature Selection among around 256 columns
* Dummy value handling with Fancy Iterative Imputation
* Comparistion between different classification models 
  -   Classic Classification - Logistic Regression,
  -   PCA - Principle Component Analysis
  -   Ensembling - Random Forest Method, 
  -   Adaboost (adaptive Boosting) Method, 
  -   Gradient Boosting Method,
  -   XG Boosting
* Applying Class-imbalance method for exactitude in 'Recall' and 'Precision' values
* Classification modeling with Hyper-parameter tuning
* Modeling with GridSearch for Out-of-bag train/test computations
