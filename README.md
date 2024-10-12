# Customer-Segmentation
Downloaded the Dataset from Kaggle (https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python) with some basic data about your customers like Customer ID, age, gender, annual income and spending score to carry out market basket analysis. CSV file was read into a dataframe using pandas The approach was to remove any unncessary information first, check for any empty values, and choosing the features to be considered for clustering as part of pre-processing. The next challenge was choosing the optimal number of clusters which we find with the help of a parameter called (WCSS) Within Clusters Sum of Squares- it finds the distance between each datapoint and their centroid (midpoint) in the cluster.With the help of an elbow graph from seaborn module it was determined that 5 clusters is optimal and this information was then injected into the **KMeans Machine Learning Model** for training. This labeled all the datapoints into clusters that they belonged in. The dataframe was then masked and plotted with the help of matplotlib.pyplot module with all the datapoints coloured different to visually distinguish the clusters and centroids were plotted too. This helped us gain valuable business insights and the data driven decision enhances chances of profit making for the organisation.
