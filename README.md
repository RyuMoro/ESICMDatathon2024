# ESICMDatathon2024
(This is a forked version)<br>
The BigQuery SQL codes here were used on team 6 AKI phenotyping. <br>
I was a member in a team of data scientists and ICU physicians.

TLDR:

In the round of "traditional" clustering, AgglomerativeClustering with clusters=4 after 1) removing features above correlation 0.9; 2) Generating polynomial features; 3) Applying PCA (0.95); 4) Removing outlier clusters.

Algorithms used for Deep Learning Clustering:<br>
Autoencoder, Variational Autoencoder, ClusterGAN, Deep Clustering Network

Deep Clustering Network has showed best scores in both K=3 and 4 (0.909 & 0.683).
No further hyperparameter tuning has not been done because an Autoencoder model has been chosen for the presentation.
