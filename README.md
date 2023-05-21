# ML-DSBA-final-project
Projects for Machine Learning I class DSBA

Adam Janczyszyn:
- responsible for regression task data cleaning and classification model creation

Jakub Żmujdzin
- responsible for classification data cleaning and regression model creation

Pycaret regression output:
```
>>> clf = setup(df, target='newborn_weight', use_gpu=True, n_jobs=-1, fold=5)
>>> compare_models(include=['lr', 'lasso', 'ridge', 'en', 'knn', 'dt', 'rf', 'ada', 'xgboost', 'dummy'])
                             Model       MAE          MSE      RMSE      R2  \                                                                                                                                                                                                                             
xgboost  Extreme Gradient Boosting  403.0712  293076.3848  541.3649  0.1598   
rf         Random Forest Regressor  413.8129  304457.5004  551.7763  0.1272   
lr               Linear Regression  413.9056  316197.6242  562.3139  0.0936   
ridge             Ridge Regression  413.9056  316197.6230  562.3139  0.0936   
lasso             Lasso Regression  413.8988  316215.5475  562.3299  0.0935   
en                     Elastic Net  416.0456  318830.7009  564.6503  0.0860   
ada             AdaBoost Regressor  431.3314  324992.0151  570.0752  0.0684   
dummy              Dummy Regressor  436.0663  348838.5427  590.6250 -0.0000   
knn          K Neighbors Regressor  450.9472  357651.2192  598.0390 -0.0253   
dt         Decision Tree Regressor  597.5788  624108.1437  790.0034 -0.7891   

          RMSLE    MAPE  TT (Sec)  
xgboost  0.2123  0.1553     0.832  
rf       0.2134  0.1570    47.774  
lr       0.2220  0.1631     0.728  
ridge    0.2220  0.1631     0.314  
lasso    0.2220  0.1631     0.970  
en       0.2227  0.1639     0.940  
ada      0.2183  0.1611    30.024  
dummy    0.2308  0.1722     0.264  
knn      0.2283  0.1717    13.842  
dt       0.3085  0.2144    10.266 
```
