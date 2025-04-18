# Clustering
I explored various clustering algorithms using different preprocessing techniques and evaluated them based on different metrics. The dataset utilized was the well-known Iris Dataset.

The clustering techniques employed were:
* K-Means Clustering (KM)
* Hierarchical Clustering (HC)
* Density-Based Spatial Clustering of Applications with Noise (DBSCAN)
* Spectral Clustering (SC)
* Affinity Propagation (AP)
* Ordering Points To Identify the Clustering Structure (OPTICS)
* Mean Shift Clustering (MS) <br>
The evaluation metrics considered were:
Silhouette Score Calinski-Harabasz Score Davies-Bouldin Score For preprocessing, I applied:

Normalization
PCA (Principal Component Analysis) Transform Scale

It's important to note that the absence of a 'scale' column in the DBSCAN results is due to DBSCAN's different approach to similarity metrics, which doesn't heavily rely on scaling as KMeans or hierarchical clustering algorithms do.

1- Kmeans
![image](https://github.com/Kriti-be21/Clustering/assets/109240831/c91955ed-3712-4d88-b469-4776d867a8be)


2- hclust
![image](https://github.com/Kriti-be21/Clustering/assets/109240831/615a1bc5-8639-4b20-bbfc-41a84e19ebad)


3- dbscan
![image](https://github.com/Kriti-be21/Clustering/assets/109240831/11f59892-9f2e-4185-ab08-3f67381fb7af)


4- sc
![image](https://github.com/Kriti-be21/Clustering/assets/109240831/0ecba7b8-7ebf-43a2-b338-aabe93337c7b)


5- optics
![image](https://github.com/Kriti-be21/Clustering/assets/109240831/b8bf32f2-f7f5-4897-94e1-0a9caecf2801)


6- meanshift
![image](https://github.com/Kriti-be21/Clustering/assets/109240831/a54a5e4c-60df-429c-9cda-f826a9136ee4)

7- ap
![image](https://github.com/Kriti-be21/Clustering/assets/109240831/bb90bd71-2194-42e0-b30d-7ff1f550f74c)
