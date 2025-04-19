# ClusteringAnalysis
Objective To compare the performance of different clustering algorithms using various preprocessing techniques and cluster sizes based on evaluation metrics.
# 🧪 Project Title
Comparative performance study of different clustering algorithms using different pre-processing techniques with varying numbers of clusters
📁 Dataset Used
Wine Dataset from UCI Machine Learning Repository.
[Wine Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_wine.html)
# 🔄 Preprocessing Techniques
* No Processing
* Normalization
* Log Transform
* PCA
* T+N (Log Transform + Normalization)
* T+N+PCA
# 🤖 Clustering Algorithms Evaluated
- KMeans
- Agglomerative (Hierarchical)
- MeanShift
# 📏Evaluation Metrics
For each algorithm and preprocessing method, the following metrics are recorded:
- Silhouette Score
- Calinski-Harabasz Index
- Davies-Bouldin Index
# 📊 Results
- KMeans and Agglomerative Clustering were tested for cluster sizes 3, 4, and 5.
- MeanShift automatically estimated clusters and gave varied results depending on preprocessing.
- Silhouette Score was higher with "No Processing" or "PCA" for KMeans.
- Silhouette Score was generally higher with "No Processing" or "T+N", especially for MeanShift.
- PCA reduced scores in some cases due to loss of original feature variance.
- Best Cluster Size was 3. Increase in cluster size reduced Evaluation scores in most cases.
