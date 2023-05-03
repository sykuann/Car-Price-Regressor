# Car-Price-Regressor
Dataset is A Chinese Car Company intend to enter the US market and we are required to model the price of cars with the available independent variables. 
The dataset contains 25 columns and 1 target feature which is the price of vehicle with 205 rows of entries.
Dataset do not have any null value and do not have any duplicated rows.
The price distribution plot is skewed to the right and the maximum number of cars are in the price range of 20000.
Dataset is split into train dataset and test dataset with the size of test dataset set at 0.1.
The first modelling we put our dataset is LGBM regressor. It scores a 0.939 r2 score with the preset parameters of n_estimators = 40.`  
The next model is Random Forest Regressor, it scores a 0.9968 r2 score and its’ mean squared error is 1t 190688.52 which shows that it is a consistent model.  
The last model we use is XGB regressor. 
It scores a 0.999 r2 score and only a 2.742 mean squared error. The accuracy and consistency of the model is very high and by far the best model for this dataset. 
