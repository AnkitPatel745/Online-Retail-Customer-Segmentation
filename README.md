![image](https://user-images.githubusercontent.com/88999980/174469645-479a7e01-f6e6-4701-bfee-9d1362bde96c.png)

# Online-Retail-Customer-Segmentation
## CONTENTS
* Introduction
* Problem Statement
* Methodology
* Loading the data
* Exploratory Data Analysis
* Treating missing values and outliers
* Feature engineering
* Data Modeling
* Conclusion

## SPREAD OF MISSING VALUES
![image](https://user-images.githubusercontent.com/88999980/174470002-bf47be01-1268-4867-aeec-8a0991d89dde.png)

## DATA MODELING 
#### Silhouette analysis on K-Means Clustering

**Silhouette analysis** can be used to study the separation distance between the resulting clusters, as a strategy to quantifying the quality of clustering via graphical tool to plot a measure of how tightly grouped the samples in the clusters are. The silhouette plot displays a measure of how close each point in one cluster is to points in the neighboring clusters and thus provides a way to assess parameters like number of clusters visually.
Let's see below how our data perform for each K clusters groups (3, 5 and 7) in the silhouette score of each cluster, along with the center of each of the cluster discovered in the scatter plots, by amount recency and frequency.

**Silhouette Analysis**
p is the mean distance to the points in the nearest cluster that the data point is not a part of
q is the mean intra-cluster distance to all the points in its own cluster.

**The value of the silhouette score range lies between -1 to 1.**
A score closer to 1 indicates that the data point is very similar to other data points in the cluster,
A score closer to -1 indicates that the data point is not similar to the data points in its cluster.


![image](https://user-images.githubusercontent.com/88999980/174470100-b28adf01-3366-4b44-823b-056c4453b4de.png)

# Hierarchical Clustering
Hierarchical clustering involves creating clusters that have a predetermined ordering from top to bottom. For example, all files and folders on the hard disk are organized in a hierarchy. There are two types of hierarchical clustering,
* Divisive
* Agglomerative
![image](https://user-images.githubusercontent.com/88999980/174470171-674a2369-e6bb-4038-a8f5-a9cb9b52bed9.png)

# FINAL 3D VISUALIZATION
![image](https://user-images.githubusercontent.com/88999980/174470223-8fb72058-9cf0-4f12-935e-c336375628be.png)



To segment the Customers based on RFM so that the company can target its customers efficiently.
