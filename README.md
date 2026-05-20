# group_clustering_unsupervised_analysis
knn workd like this: 

    Randomly pick k centroids from the examples as initial cluster centers
      Assign each example to the nearest centroid, 
      Move the centroids to the center of the examples that were assigned to it
      Repeat steps 2 and 3 until the cluster assignments do not change or a user-defined tolerance or maximum number of iterations is reached

To measure the similarity between objects we use for continous featueres,  squared Euclidean distance between two points, x and y, in m-dimensional space:
![alt text](image.png)

cluster inertia:
![alt text](image-1.png)

![alt text](image-2.png)
