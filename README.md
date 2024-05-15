# CryptoClustering
Module 19 Challenge


For this challenge we are using crypto-currency data to create predictions on the affect of daily and weekly price changes.

I began by using the StandardScaler to scale the numeric data. Then I used the elbow method on the scaled data to find the best value for k and created a K-means model using the original data to find clusters. The next thing I did was use Principle Component Analysis to find the top 3 principle components, which comprise 89.5% of the explained varience. I used the elbow method on the PCA data to find the optimal number of clusters (k) and create a K-means model using the original data. 


I did not use any outside sources for this code. 