# House-Price-Prediction-Project

This project predicts the price of a house by taking in parameters such as locality,area(sqft),number of bathrooms,bhk.
It starts with loading the dataset followed by cleaning it which involves dropping the rows with missing values.
Next comes Feature engineering which includes manipulation of our data set in order to improve the training of our machine learning model leading to better performance and greater accuracy.
Next comes the removal of oultiers which contributes to accuracy of our ML model.
Now, we split our dataset for training and testing.Here, we are preparing our data to fit in our models.
In this stage, we create our ML models using linear regression, lasso, decision tree.We create a function which compares the r2 values of the all the three models and selects the best amongst them.
Last but not least, we create a function where we can pass the parameters required for price prediction and try it out.
