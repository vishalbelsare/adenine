=====================================
ADENINE (A Data ExploratioN pIpeliNE)
=====================================

**adenine** is a machine learning and data mining Python pipeline that helps you to answer this tedious question: are my data relevant with the problem I'm dealing with?

The main structure of adenine can be summarized in the following 3 steps.
	
1. **Preprocessing:** Have you ever wondered what would have changed if only  your data have been preprocessed in a different way? Or is data preprocessing is a good idea at all? adenine offers several preprocessing procedures, such as: data centering, Min-Max scaling, standardization or normalization and allows you to compare the results of the analysis conducted with different starting point.


2. **Dimensionality Reduction:** In the context of data exploration, this  phase becomes particularly helpful for high dimensional data (e.g. -omics scenario). This step, generically named DR, may actually include some manifold learning   (such as Isomap, Multidimensional Scaling, etc), supervised (Linear   Discriminant Analysis) and unsupervised (Principal Component Analysis, kernel PCA) techniques.


3. **Clustering:** This section aims at grouping data into clusters without taking into account the class labels. Several techniques such as K-Means, Spectral or Hierarchical clustering will work on both original and dimensionality reduced data.


The final output of adenine is a compact and textual representation of the results obtained from the pipelines made with each possible combination of the algorithms
implemented at each step.