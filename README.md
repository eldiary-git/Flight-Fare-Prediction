# Flight-Fare-Prediction

- the project target is to predict the Flight Fare based on the uploaded data which contain the price, the time, the destination for many travels 
-   
1) remove null values from the dataset
2) convert the object data type to timestamp with (datetime) and split many columns to specific and detailed columns to increase the performance of the model.
3) using (OneHotEncoding) with many columns because the columns is a ( nominal categorical )
4) concatenote the training data features together
5) Preprocessing the test data
6) using ExtraTreesRegressor to work on the important feature
7) split the data 
8) use ( RandomForestRegressor ) then get the prediction
9) get the highest possible accuracy for training data (0.9) 
10) get the highest possible accuracy for test data (0.9) 
