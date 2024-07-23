# ESICMDatathon2024
Working files for the Team 5: AKI phenotyping. <br>
I was a member in a team of data scientists and ICU physicians.

Main Files:

[Cluster.ipynb](https://github.com/RyuMoro/ESICMDatathon2024/blob/ffc73707885e67223383c1781dd72e7d00818e86/Cluster.ipynb):
The notebook for clustering.

[__FINAL ABSTRACT](https://github.com/RyuMoro/ESICMDatathon2024/blob/ffc73707885e67223383c1781dd72e7d00818e86/__FINAL%20ABSTRACT%20-%20DATATHON%20FINALS%20-%20Exploring%20Acute%20Kidney%20Injury%20Complexity_%20Comparing%20Two%20Unsupervised%20Cluster%20Analysis%20Methods%20to%20Identify%20Phenotypic%20Patterns%20in%20Critical%20Care%20Patients.pdf):
The final abstract document for the event. It explains our project from both a medical and a data science point of view.

Other notebooks:
They mainly contain the data extraction process with SQL, the data preprocessing and the clustering.

TLDR:

In the round of traditional clustering, AgglomerativeClustering with K=4 showed the best result with a silhouette score of 0.55 after 1) removing features above correlation 0.9; 2) generating polynomial features; 3) applying PCA (0.95); 4) removing outlier clusters.

Algorithms used for deep learning clustering:<br
Autoencoder, Variational Autoencoder, ClusterGAN, Deep Clustering Network

Deep Clustering Network showed the best results in both K=3 and 4 (0.909 & 0.683).
No further hyperparameter tuning was done because an autoencoder model was chosen for the presentation.
