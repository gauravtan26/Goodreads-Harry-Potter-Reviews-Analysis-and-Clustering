# Goodreads: Harry Potter Review Analysis and Clustering
Review Analysis and Text Clustering for extracting topics from reviews on Harry Potter Books 

## Introduction
Here, we are trying to analyse the reviews on Harry Potter Books given by readers on Goodreads. By analysing the data, we will try to find the answers of the following questions:
1. Is the interest of people in Harry Potter books declining as time is passing?
2. Which is the highest-rated Harry Potter book on Goodreads?
3. Which is the lowest-rated Harry Potter book on Goodreads?
4. What do users write as reviews on Harry Potter Books?

## Distribution of the number of reviews with time
<img src="https://user-images.githubusercontent.com/65237445/149659085-61ce5f20-8aa5-4f1f-ab29-c0faf537df66.PNG" width="400" height = "400">

## Average Ratings 
<img src="https://user-images.githubusercontent.com/65237445/149659172-d6de6226-4687-427e-907f-5b8361db4c06.png" width="400" height = "300">

## Brief Introduction to K-Means
K-means is a common method of clustering in data science and can be easily implemented via the Python library Scikit-Learn (see Part Two of this book). The K-means method of clustering takes in the textual data and places all documens in k number of clusters. In this scenario, the researcher assigns a numerical variable for k, so if the researcher wished to see all texts clustered into 10 topics, or clusters, the k-means algorithm would find the documents with the greatest degree of similarity and place them in the closest mean cluster. The result is a forced clustering of all texts neatly into 10 clusters. We can then discern their topics by examining the words that overlap between texts in each cluster.

In the example below, we can see a sample output of K-Means clustering. In this image, there are 3 clusters. Notice how all data (dots on the graph) are clustered into one of the three categories. This is the K-Means clustering method at work.
## Text Cluster
<img src="https://user-images.githubusercontent.com/65237445/149658485-8280f0b2-f2cf-482a-b588-a5f24f7ca844.PNG" width="400" height = "400">
