# Cryptocurrencies
Module 18

Overview: 
The purpose of this project was to analyze a dataset from many alternative cryptocurrencies to spot trends that make a firm or person want to invest in them. The problem with cryptos is that the most common ones, like bitcoin or ethereum, are becoming unaffordable for the common public. I will be using unsupervised machine learning to see if we can spot any trends that result in opportunities of these altcoins.The algorithms and techniques emphasized that were used here were clustering, K-Means, and Principal components Analysis. 


Results: 
First, I Loaded the data, and transform the data so that unsupervised machine learning could work.
Initial Dataframe Head 

![Step 1-1](https://user-images.githubusercontent.com/95897182/166161180-143985d3-f57a-4e6b-a202-8242241a1524.png)

Next Step, the data was scaled, fit, and transformed in preparation for a Principal Component Analysis (PCA)

![Step 2](https://user-images.githubusercontent.com/95897182/166161324-c933bd40-fb31-4ecb-89a6-2cf658dc65ca.png)

![Step 3](https://user-images.githubusercontent.com/95897182/166161396-0312b935-7621-43ea-bc47-b73ddc120e7d.png)

![elbow](https://user-images.githubusercontent.com/95897182/166161490-13d3ccba-5a4c-4171-b8cf-095d1b0d278f.png)

The optimal result was 4 clusters therefore I then proceeded with the KMeans analysis to fit the pca dataframe and predict the clustering. 
The product was this clustered_df with a 'Class' column that showed the predictions to which group it belonged to.

![Step 5](https://user-images.githubusercontent.com/95897182/166161607-a1590e5c-b36e-4f88-865b-874b75fd8f70.png) 


To Visualize the clusters, a 3D Graph was Created and then Plotted. 











