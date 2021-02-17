# DataAnalysisWineDataset
I obtained the data by incorpating a csv file of white_wine dataset, which is located on the notebook root directory,
then I explored the dataset by using the shape property, I discoverd that the dataset has **12 features, and 4898 data points**. 
Secondly I used the shuffle function from the scikit learn library, this helps reorganize the data to do the random permutaion and combination.
I visualized two features from the dataset on a scatter plot to find any correlation between the variables.

In task 2, I used an unsupervised learning approach to reduce the number of dimension in the dataset by doing a PCA Analysis.
The number of pca components are kept at 2, it can also be noticed that around 98% percent of the variance was captured by the first and the second component. 
The scatter plot depicts the clusters of data point as per their quality. it can be observed that the points are randomly distributed between PCA_0 and PCA_1. The following bar plot shows the amount of variance caputured by each component

In task 3, the data is divided among three different sets, secondly the data is further splitted by using train_test_split function.

In task 4, it can be observed from the learning curve that as the number of training size increases the gap between validation and training set is converging, furthermore when the train size was under 300 the mean square error was -1.4 for the training set, but as the training and validation size gradually increased the model performance also improved

- **b. For Task 4, discuss whether there is any problem with that experimental design. If there
is, what is it? How may you further improve it so that the experimental results are more
reliable?**

I applied linear regression on the dataset, and mean square error metrics to check the model accuracy. The error was 0.7734699436661941, 
I think if we try other classification models to check if there is any improvement in the model overall performance, apart from that,
in task 2 PCA was performed on the dataset, and perhaps including PCA components in the dataset that is supplied to linear regression model could fix the problem within the 
experimental design
