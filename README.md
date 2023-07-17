# Stock-Prediction-using-Support-Vector-Regression
ML Python Project

---------------------------------------------------------------------------------------

Note :- All the code in this project has been tested and run successfully in Google Colab. I encourage you to try running it in Colab for the best experience and to ensure smooth execution. Happy coding!

---------------------------------------------------------------------------------------


The provided code performs the following steps:

1. Import the required libraries: `pandas`, `numpy`, `matplotlib.pyplot`, and `files` from `google.colab`.
2. Upload a CSV file named 'data.csv' using the `files.upload()` function.
3. Read the uploaded CSV file into a pandas DataFrame called `dataset`.
4. Print the shape and the first 5 rows of the dataset to check its structure and content.
5. Extract the feature variables (`X`) and the target variable (`Y`) from the dataset.
6. Reshape the target variable to have the desired shape.
7. Split the dataset into training and testing sets using the `train_test_split` function from `sklearn.model_selection`.
8. Create three Support Vector Regression (SVR) models: `model1`, `model2`, and `model3`. `model1` uses the default settings, `model2` has a linear kernel with degree 2, and `model3` has a polynomial kernel with degree 3.
9. Fit each model on the training data using the `fit` method.
10. Predict the target variable for the test data using each model and store the predictions in `ypred1`, `ypred2`, and `ypred3`.
11. Calculate the root mean square error (RMSE) and R2 score for each model using the `mean_squared_error` and `r2_score` functions from `sklearn.metrics`.
12. Print the RMSE and R2 score for each model.

The code uses SVR models with different kernel functions (linear and polynomial) to predict the target variable based on the provided feature variables. It evaluates the performance of each model by calculating the RMSE and R2 score, which provide insights into the accuracy and goodness of fit of the models.
