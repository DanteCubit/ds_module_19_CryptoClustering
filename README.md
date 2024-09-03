# ds_module_19_CryptoClustering
Using unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

Code was accomplished following the lesson plans, week 19, day 3, activity 4 and 5.

First I used the Standar Scaler to normalize the data and created a new DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

Then I Use the elbow method to find the best value for k and clustered the cryptocurrencies for the value for k on the original scaled data and then created a scatter plot of the clusters.

Then Using the original scaled DataFrame, I performed a PCA and reduced the features to three principal components. Created a new DataFrame with the PCA data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

Using the same method from before, I found the best value for K using the PCA Data, then plotted the clusters.

