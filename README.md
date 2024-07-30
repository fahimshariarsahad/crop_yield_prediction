# crop_yield_prediction
The project aims to predict crop yield based on environmental factors such as crop, precipitation, humidity, temperature etc. Crops selected for this project are Cocoa beans, Fruit palm oil, Paddy rice, Natural rubber.


## Executive summary

Project involves the use of Linear Regression(LR), Support Vector Regression(SVR), Decision Tree(DT), Random Forest Regression(RF) and Xgboost(Xgb) to measure the possible best outcome. Notably Random Forest, Xgboost and Decision Tree provided better Adjusted R<sup>2</sup> value correspondingly RF=0.993, DT=0.992, Xgb=0.989, LR=0.988, SVR=0.968. Tools such as Pandas, NumPy, Seaborn and Matplotlib are used for building the project. The dataset consisted of 156 rows and 6 columns, with a 70/30 split for training and testing data.


## Technical overview

Below I outline briefly the main steps in the workflow that i have done with the  Jupyter notebook.

| Task | Summary |
| --- | --- |
| Explore and clean data | Exploring data, their rows and features also impute missing values. |
| Feature engineering | Converting character type data into integer type using suitable methods. |
| Select algorithm | Compare a number of algorithms using cross validation to identify the most promising performers for this data/feature set. |
| Establish model performance | Use a 30% hold-out test set to compare predicted and observed yields. |



## Future work

for future work there is still many things we can work on, for now these issues could be addressed by:

* getting more data,
* more different features that can play a vital role in this perspect,
* fine tuning the model using various suitable techniques,or
* using ensemble techniques by combining the results of different models.
