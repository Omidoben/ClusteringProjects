
# Wine Data Clustering and PCA Analysis



## Project Overview
This project focuses on the analysis and clustering of a wine dataset adopted from Kaggle, containing 13 chemical properties of wines such as alcohol and malic acid. The dataset is ideal for unsupervised learning techniques, as it does not include any outcome variable.

## Project Workflow:
#### EDA
Conducted EDA to examine the distribution of variables and the correlation between them. This step provided insights into the data's structure and guided the choice of clustering techniques.

#### K-means Clustering
Applied k-means clustering using the tidyclust package to group the wines into clusters. The silhouette average score was used to evaluate the clustering performance, helping to determine the optimal number of clusters.

#### Hierarchical Clustering

Performed agglomerative hierarchical clustering to explore whether this method could improve clustering performance compared to k-means. The results were analyzed and compared.
#### Principal Component Analysis (PCA):

Conducted PCA to reduce the dimensionality of the dataset and identify patterns. This step also helped address multicollinearity among the variables. The PCA step was then incorporated into the k-means model, resulting in improved clustering performance.

