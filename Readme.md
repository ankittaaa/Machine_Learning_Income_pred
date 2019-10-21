README.md

The given model is built as a part of Machine Learning module for TCD kaggle ML competition.
The provided data set had a list of people and their various related information like hair color, height, country and a number of other features.
I used Random Forest algorithm to predict the yearly salaries of all people.
 The libraries used in building this model are numpy, pandas and sklearn.
 The steps followed in this project are as follows - 
 1. Loading the given data 
 2. Preprocessing : Null values were removed, Handled missing data, Dropping the 'Instance' column.
 3. Perform one hot Encoding on all the categorical columns. 
 4. Create the Random Forest Regressor model. 
 5. Fitting the model to training set.
 6. Formulating predictions using test data. 
 7. Computing Root Mean Squared Error(RMSE).
