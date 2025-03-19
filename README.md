# module_19 challenge assignment
crypto_clustering

##### Background/Overview:

Use Python and unsupervised learning to predict and analyze cryptocurrencies, specifically assessing the impact of 24-hour and 7-day price changes.

---

##### Analysis & Conclusions:

Using fewer features to cluster the data using K-Means, as achieved through Principal Component Analysis (PCA), has several impacts:

**Dimensionality Reduction :** PCA reduces the number of features while retaining most of the variance in the data. This simplifies the clustering process and can lead to more distinct and interpretable clusters.

**Cluster Separation :** In the PCA-transformed data (right plot), the clusters appear more separated compared to the original feature space (left plot). This indicates that PCA helps in highlighting the underlying structure of the data, making the clusters more distinguishable.

**Noise Reduction :** By focusing on the principal components, PCA reduces the impact of noise and less important features. This can lead to more robust and stable clustering results.

**Visualization :** With fewer features, it becomes easier to visualize the clusters in a 2D or 3D space. This aids in better understanding and interpreting the clustering results.

**Computational Efficiency :** Reducing the number of features can also improve the computational efficiency of the K-Means algorithm, as it has fewer dimensions to process.

**Conclusion:**

Using fewer features through PCA for clustering with K-Means can lead to more distinct and interpretable clusters, reduce noise, improve visualization, and enhance computational efficiency. However, it is essential to ensure that the principal components retain enough variance to represent the original data accurately.

---

##### References:

Data and starter code prepared and provided by edX Boot Camps 

Andrew Lane (github: andrewplane) assisted with refining the code for the PCA dataframe values
