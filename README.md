# Goodreads: Harry Potter Review Analysis and Clustering
Text Clustering for extracting topics from reviews on Harry Potter Books 

## Brief Introduction to K-Means
K-means is a common method of clustering in data science and can be easily implemented via the Python library Scikit-Learn (see Part Two of this book). The K-means method of clustering takes in the textual data and places all documens in k number of clusters. In this scenario, the researcher assigns a numerical variable for k, so if the researcher wished to see all texts clustered into 10 topics, or clusters, the k-means algorithm would find the documents with the greatest degree of similarity and place them in the closest mean cluster. The result is a forced clustering of all texts neatly into 10 clusters. We can then discern their topics by examining the words that overlap between texts in each cluster.

In the example below, we can see a sample output of K-Means clustering. In this image, there are 3 clusters. Notice how all data (dots on the graph) are clustered into one of the three categories. This is the K-Means clustering method at work.
## Text Cluster
<img src="https://user-images.githubusercontent.com/65237445/149658485-8280f0b2-f2cf-482a-b588-a5f24f7ca844.PNG" width="400" height = "400">
