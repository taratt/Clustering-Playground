# Clustering-Playground
This project is done as an assignment for Data Mining course at Amirkabir University of Technology and aims to cluster items from a variety of datasets.
<br>
(Unfortunately this notebook is not rendered correctly by github)
## Part I
In this part, first, the dataset is created using make_blob method from sklearn_datasets. Next kmeans clustering is done on the created dataset and K (the number of clusters in kmeans algorithm) is tuned using different thumbrules and methods such as the elbow rule.
## Part II
This section aims to cluster images of digits from loaded using load_digits from sklearn_datasets. Kmeans clustering is done on the dataset with k=10 and centers of each cluster is plotted.
<br>
Next dimensionality reduction is done using Isomap algorithm and each item in the dataset is reduced to two dimensions. After that two diagrams are plotted. The first diagram shows the distribution of labels of the digits and the second one shows the distribution of the target values predicted after kmeans clustering and finding the closest cluster to each digit in the dataset. It can be observed that the two diagrams are very much similar to eachother thus clustering is done accurately as a preprocessing step to the classification.
## Part III
In this section an image's size is reduced using clustering. The colours in the image are clustered into four clusters and then each colour is replaced with the centroid of its corresponding cluster.
## Part IV
In this section DBSCAN is implemented and K nearest neighbours alogirthm alongside k-distance graph and the elbow rule is used to find the best epsilon for this algorithm. Next Minpts is tuned to get the best results from DBSCAN.
