# Lab-5

In this code, we first load the iris dataset using the load_iris function from the sklearn.datasets module. We then convert the dataset to a pandas dataframe and add the target variable (species) to the dataframe.

Next, we generate a scatter plot matrix using the pairplot function from the seaborn module. We set the hue parameter to the target variable to visualize the relationship between each pair of variables for each species.

Finally, we generate a heatmap using the heatmap function from the seaborn module. We pass the correlation matrix of the variables in the iris dataset to the data parameter of the function. We also set the annot parameter to True to display the correlation coefficients on the heatmap.

The resulting scatter plot matrix and heatmap will help us identify the relationships among different variables in the iris dataset. The scatter plot matrix will help us visualize the pairwise relationships between the variables for each species, while the heatmap will help us visualize the correlation coefficients between the variables.
