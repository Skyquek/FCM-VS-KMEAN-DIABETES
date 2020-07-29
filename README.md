# Fuzzy C-Mean Clustering and Hard C-Mean Clustering

### Abstract
The blooming of machine learning and deep learning is starting to raise the demand for using data to solve our real-world problem. But not all the data collected is crisp, which may contain fuzziness. Unsupervised clustering in a fuzzy logic or fuzzy c-mean is one of the most commonly used methods in data mining when dealing with uncertainty or vague dataset. In this paper, we will study the difference between the clustering method of using the Hard C-Mean and Fuzzy C-Mean method. We will highlight the best cluster found by HCM and FCM. 


### Hard c-means
Hard C-Mean is also known as hard clustering. A very well-known method is known as K-Mean clustering. K-Mean Clustering is used to classify data in a crisp sense. This method will only classify a data point to only one cluster. 

The first step of computing k-mean is we need to determine the number of the cluster we desired. Next, we will need to assign each of the points to the closest centroid, and each of the collection of the points assigned to the centroid is considered as one cluster.  After that, the centroid of the original cluster will be kept on updating based on the points assigned in the cluster. The steps above are repeated until the centroid didn’t change or remains constant. 

In the K-Mean clustering algorithm, the data points are cluster together based on the similarity. Typically, we will use euclidean distance to find out squared of the distance between each variable. 

### Fuzzy c-means
We had review how hard c-means or k-mean, now we will be review how fuzzy c-means work. Fuzzy clustering also known as soft clustering is based on the Zadeh’s idea which introduced in 1965.

Unlike k-means clustering that cluster the datapoint to crisp set which is 0 and 1, fuzzy c-means algorithm assigned vectors to all the cluster with the membership value at the interval 0 to 1.  
