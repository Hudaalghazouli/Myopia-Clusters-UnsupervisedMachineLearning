# Myopia Clusters
Hsh
I applied what I learned about unsupervised learning by fitting data to a model and using clustering algorithms to place data into groups. Then, I created a visualization that shared my findings.

## Breaking down the project into four parts:

* Part 1: Prepared the Data

* Part 2: Applied Dimensionality Reduction 

* Part 3: Performed a Cluster Analysis with K-means

* Part 4: Made a Recommendation 

### Part 1: Preparing the Data

1. Read `myopia.csv` into a Pandas DataFrame.

2. Removed the "MYOPIC" column from the dataset.

3. Standardized the dataset so that columns that contain larger values do not influence the outcome more than columns with smaller values.

### Part 2: Applied Dimensionality Reduction

1. Performed dimensionality reduction with PCA "preserved 90% of the explained variance in dimensionality reduction."

2. Further reduced the dataset dimensions with t-SNE and visually inspect the results. 

3. Created a scatter plots of the t-SNE output.

### Part 3: Performed a Cluster Analysis with K-means

Created an elbow plot to identify the best number of clusters.

### Part 4: Made a Recommendation

Unfortunately the whole output doesn’t make that much sense, and from the elbow plot we can see that there is roughly two or three clusters. Can't make a clear recomandation but from the scotter plots we can tell that TSNE is not a good option!
