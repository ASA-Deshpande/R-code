# R-code
## Mall Customers Segmentation in R. The project was a form of assessment in the Data Science course.
@tanishq252 contributed to the project for the Support Vector Regression model. 

_Kaggle dataset of 200 records was used._ [This is the dataset](https://www.kaggle.com/shwetabh123/mall-customers)

Data pre-processing and visualization of the data was done. Here are some of the plots-

The following algorithms were used:-
1. Support Vector Regression
2. Multiple Linear Regression 
3. K-means Clustering
4. k-nearest neighbours for the classification problem
5. Support Vector Machines for the classification problem
6. RandomForest for the classification problem

MLR and SVR was used for determining the variables with the highest linear correlation to the Spending Score, {Age, here} for exploration purposes.

Elbow Method for finding the optimal number of clusters revealed 5 as the optimum number of clusters as shown.

Here are the visualized clusters-

The original dataset was then modified by dividing the Spending Score into 3 levels- 'Minimal', 'Medium' and 'Excess' and a classification problem was created. The training dataset was fed to 3 models; namely KNN, SVM and RF, out of which RF had the best accuracy and hence was used to make predictions on the test dataset with a final accuracy of 87.5%.
