# Lab-5

#SCATTER PLOT MATRIX AND HEATMAP OF THE IRIS DATASET

In this code, we first load the iris dataset using the load_iris function from the sklearn.datasets module. 
We then convert the dataset to a pandas dataframe and add the target variable (species) to the dataframe.
Next, we generate a scatter plot matrix using the pairplot function from the seaborn module. 
We set the hue parameter to the target variable to visualize the relationship between each pair of variables for each species.
Finally, we generate a heatmap using the heatmap function from the seaborn module. 
We pass the correlation matrix of the variables in the iris dataset to the data parameter of the function. 
We also set the annot parameter to True to display the correlation coefficients on the heatmap.
The resulting scatter plot matrix and heatmap will help us identify the relationships among different variables in the iris dataset. 
The scatter plot matrix will help us visualize the pairwise relationships between the variables for each species. 
While the heatmap will help us visualize the correlation coefficients between the variables.

#LINEARLY SEPARABLE CLASS OF THE IRIS DATASET

In this code, we first load the Iris dataset using the load_iris function. 
We then split the data into training and testing sets using the train_test_split function from the sklearn.model_selection module.
Next, we train a logistic regression model on the training set using the LogisticRegression class from the sklearn.linear_model module. 
We then evaluate the accuracy of the model on the testing set using the score method.
Finally, we check which classes are linearly separable by looking at the coefficients and intercept of the logistic regression model. 
If the coefficients and intercept allow us to draw a linear boundary between two classes, then those classes are linearly separable.
In the Iris dataset, we have three classes: Iris setosa, Iris versicolor, and Iris virginica. 
We get an accuracy score of 1.0, which means that the logistic regression model is able to perfectly classify the testing set. 
This suggests that none of the classes are linearly separable from the others.

#EXPLANATORY GRAPHICS OF THE ADULT DATASET

In this code, we first load the Adult dataset using the read_csv function from the pandas module. 
We then perform various exploratory data analysis tasks, such as checking the dataset shape, head, info, summary statistics, missing values, and unique values.
Next, we visualize the distribution of the target variable (income) using a countplot from the seaborn module. 
We then visualize the distribution of the categorical variables using countplots with the hue parameter set to the target variable.
Finally, we visualize the correlation between the numerical variables using a heatmap from the seaborn module. 
We also visualize the distribution of the numerical variables using histograms with the hue parameter set to the target variable.
The resulting EDA and explanatory graphics will provide insights into the Adult dataset, such as the distribution of the target variable and the relationships between the variables in the dataset.
