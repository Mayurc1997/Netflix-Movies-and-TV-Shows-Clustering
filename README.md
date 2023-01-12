# Netflix-Movies-and-TV-Shows-Clustering


* LDA and LSA has sorted much more similar titles in a group of genre

* Recommendation system works perfectly well with description column

* After applying K - means optimal value of number of clusters is 4

* Silhouette score for a set of sample data points is used to measure how dense and well-separated the clusters are.


# CONCLUSIONS :
1)There are about 70% movies and 30% TV shows on Netflix.

2)Data set contains 7787 rows and 12 columns in that cast and director features contains large number of missing values so we can drop it and we have 10 features for the further implementation

3)The United States has the highest number of content on Netflix by a huge margin followed by India.

4)Raul Campos and Jan Sulter collectively have directed the most content on Netflix.

5)Anupam Kher has acted in the highest number of films on Netflix. Drama is the most popular genre followed by comedy.

6)More of the content is released in holiday season - October, November, December and January.

7)The number of releases have significantly increased after 2015 and have dropped in 2021 because of Covid 19.

8)By applying the silhouette score method for n range clusters on dataset we got best score which is 0.348 for 3 clusters it means content explained well on their own clusters, by using elbow method after k = 3 curve gets linear it means k = 3 will be the best cluster

9)Applied different clustering models Kmeans, hierarchical, Agglomerative clustering on data we got the best cluster arrangments

10)By applying different clustering algorithms to our dataset .we get the optimal number of cluster is equal to 3
