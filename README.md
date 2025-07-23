In this project I needed to implement machine learning inorder to predictstudent grades in a future quarter.
The data used is from the UC Irvine's machine learning repository. 
The data was explored so I could have a complete understanding of every feature.
Multiple visualizations were created to have a deeper understanding of the dataset. 
A correlation matrix was created to see which features are correlated to the student's grades.
A feature selection algorithm was created to automatically select the best features based on how strong they correlate with the student's grades.
A custom transformer is used to store the absence values for each term.
Multiple pipelines are used to fill in missing values, feature scale, and one-hot encode the data.
A linear regression, ridge regression, and a lasso regression are performed on the training data and the models are compared using RMSE scores.
A grid search is used to fine-tune the parameters of the best regression model.
A final model in created using the new optimized paramters.
The cross validation findings of the new model are calculated and the regression line of the model along with predicted vs actual grade scores.
