# ML-DSBA-final-project
Projects for Machine Learning I class DSBA

Adam Janczyszyn:
- responsible for regression task data cleaning and classification model creation

Jakub Żmujdzin
- responsible for classification data cleaning and regression model creation

Pycaret regression output:
```
>>> compare_models(include=['lr', 'lasso', 'ridge', 'en', 'knn', 'dt', 'rf', 'ada', 'xgboost', 'dummy'])
                             Model       MAE          MSE      RMSE      R2                                                                                                                                                                                                                             
xgboost  Extreme Gradient Boosting  407.1482  297011.6268  544.9873  0.1394   
rf         Random Forest Regressor  416.2752  308260.7750  555.2119  0.1068   
lr               Linear Regression  412.6035  312624.2395  559.1277  0.0941   
lasso             Lasso Regression  412.6003  312641.0540  559.1427  0.0941   
ridge             Ridge Regression  412.6035  312624.2410  559.1277  0.0941   
en                     Elastic Net  414.6903  315157.5056  561.3884  0.0868   
dummy              Dummy Regressor  434.4514  345103.7087  587.4551 -0.0000   
knn          K Neighbors Regressor  452.8505  361581.8425  601.3164 -0.0478   
ada             AdaBoost Regressor  516.1185  421239.3004  648.7199 -0.2206   
dt         Decision Tree Regressor  602.3232  630139.8300  793.8123 -0.8260   
```
