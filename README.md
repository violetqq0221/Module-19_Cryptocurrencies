# Module 19 cryptocurrency market analysis 
## part 1: Preprocessing the data for PCA
   * clean the data set. drop " column" and remove rows which are null value
   * filter the dataframe
   * create a new dataframe for text features
   * Create variables for text features by using get dummines()
   * standarize  the features from DataFrame with StandardScaler().
   
## part 2 :Reducing Data Dimensions Using Principal Component Analysis PCA
   * using PCA to reduce dimension to to three principal components. by pca = PCA(n_components=3)
   * Create a DataFrame with the three principal components.
 
## part 3 :Clustering Cryptocurrencies Using K-means
   * plot the data by using hvPlot
   * finding the k value by elbow curve

## part 4 :Visualizing Cryptocurrencies Results
   * Creating a 3D-Scatter with the PCA data and the clusters 
   * Create the new dataset and a hvplot.scatter plot using x="TotalCoinsMined" and y="TotalCoinSupply".

