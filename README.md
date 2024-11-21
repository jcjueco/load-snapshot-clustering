# On Labeling Anomalous Load Data Using Time Series-to-Image Encoding and K-Means Clustering Method with Historical Ground Truth Evaluation

Abstract

Accurately clustering and labeling anomalous time series load data from large databases remains challenging due to close similarity and subtle deviations between each observation. This paper addressed the problem with a novel clustering model that cleaves into encoding the load data as images using a modified Gramian Angular Field (GAF) and clustering the anomalous images using K-means. Encoding load data as images enables visual interpretability, which model can distinctively cluster the load data from the temporal and visual features. To evaluate the model, we performed internal and external measures between different values of k to determine the appropriate number of clusters. The average silhouette score of the clustered encoded images is between 0.20 and 0.55. Also, the method consistently yields a minimum Davies-Bouldin Index (DBI) and maximum Calinski-Harabasz Index(CHI) across different datasets for k=2 , a competitive value against the time series clusters. This suggests the method is suitable for accurately labeling anomalous data from the set. Experimental results are verified to match ground truth historical events correctly.


<bold> Citation <bold>

@inproceedings{jueco2023labeling,
  title={On Labeling Anomalous Load Data Using Time Series-to-Image Encoding and K-Means Clustering Method with Historical Ground Truth Evaluation},
  author={Jueco, Jayson C and Navarro, Wynn Gaudette P and Libre, Lester Mel B and Undalok, Zyril Mark D and Dingcong, Clint Kyle K and Batayola, Ferdinand F and Radaza, Marvin A and Narvios, Wilen Melsedec O and Fernandez, Xavier Julian P and Baguio, Ike A},
  booktitle={2023 IEEE 15th International Conference on Humanoid, Nanotechnology, Information Technology, Communication and Control, Environment, and Management (HNICEM)},
  pages={1--6},
  year={2023},
  organization={IEEE}
}
