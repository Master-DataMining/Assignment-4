# Assignment-4

## **K-Means Clustering**

#### K-means is a centroid-based or partition-based clustering algorithm.  This algorithm partitions all the points in the sample space into K groups of similarity. The similarity is usually measured using Euclidian Distance.

## **Hierarchical Clustering**

#### Hierarchical clustering also known as hierarchical cluster analysis (HCA) is also a method of cluster analysis which seeks to build a hierarchy of clusters without having fixed number of cluster. 

## **GMM Clustering**

#### As its name implies, each cluster is modelled according to a different Gaussian distribution.

## **DB Scan Clustering using pycaret library**

#### DBScan is a density-based clustering algorithm. The key fact of this algorithm is that the neighbourhood of each point in a cluster which is within a given radius (R) must have a minimum number of points (M).

## **Conclusion:**

### Advantages of K-Means

- Easy to understand and implement.

- Can handle large datasets well.

### Disadvantages of K-Means
- Sensitive to number of clusters/centroids chosen. Even after using techniques like Elbow method, it is sometimes hard to generate good clusters.

- Does not work well with outliers. Centroids can get dragged by the outliers resulting in skewed clusters.

- Gets difficult in high dimensional spaces as the distance between the points increases and Euclidean distance diverges.

- Gets slow as the number of dimensions increases.

---
### Advantages	of Hierarchical	clustering
- Hierarchical	clustering	outputs	a	hierarchy. Therefore,	it	is	easier	to	decideon	the	number	of	clusters	by	looking	at	the	dendrogram.

- Easy	to	implement	

### Disadvantages	of Hierarchical	clustering
- It	is	not	possible	to	undo	the	previous	step:	once	the	instances	have	been	assigned	to	a	cluster,	they	can	no	longer	be	moved	around.	

- Time	complexity:	not	suitable	for	large	datasets

- The	order	of	the	data	has	an	impact	on	the	final	results	

- Very	sensitive	to	outliers

---

### Advantages of DBSCAN
- Works well for noisy datasets.

- Can identity Outliers easily.

- Clusters can take any irregular shape unlike K-Means where clusters are more or less spherical.

### Disadvantages of DBSCAN
- Does not work very well for sparse datasets or datasets with varying density.

- Sensitive to eps and minPts parameters.

- Not partitionable for multiprocessor systems.
