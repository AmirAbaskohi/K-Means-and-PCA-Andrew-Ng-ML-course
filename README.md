# K-Means and PCA implementation Andrew Ng ML course

This is solution for `Andrew Ng` ML Course in `Coursera` which implements K-Means (data clurstering) and PCA.

## What is PCA
The principal components of a collection of points in a real p-space are a sequence of p direction vectors, where the i th ith
vector is the direction of a line that best fits the data while being orthogonal to the first i − 1 vectors. Here, a best-fitting line
is defined as one that minimizes the average squared distance from the points to the line. These directions constitute an orthonormal basis in which different individual dimensions
of the data are linearly uncorrelated. Principal component analysis (PCA) is the process of computing the principal components and using them to perform a change of basis on the data,
sometimes using only the first few principal components and ignoring the rest. 

## What is data clustering?
luster analysis or clustering is the task of grouping a set of objects in such a way that objects in the same group (called a cluster) are more similar
(in some sense) to each other than to those in other groups (clusters). It is a main task of exploratory data analysis, and a common technique for statistical data
analysis, used in many fields, including pattern recognition, image analysis, information retrieval, bioinformatics, data compression, computer graphics and machine learning. 

## What is K-Means?
k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each 
observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a partitioning of
the data space into Voronoi cells. k-means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances, which would be the 
more difficult Weber problem: the mean optimizes squared errors, whereas only the geometric median minimizes Euclidean distances. For instance, better Euclidean solutions can 
be found using k-medians and k-medoids. 

# Requirements
You need to have `Octave` or `Matlab` on your system.

# How to run?
In ex7 directory run below commands:
```
octave ex7.m
octave ex7-pca.m
```

*Made by Amirhossein Abaskohi*
