# Clustering
Check out different clustering algo's as they show different scores and also the crazy conclusions the data showed!
This project performs customer segmentation using clustering algorithms on a shopping mall dataset. The goal is to group customers based on behavior and demographics to derive insights for targeted marketing.

The dataset contains the following features: Gender, Age, Annual Income (k$), and Spending Score (1-100). Basic preprocessing is done including encoding categorical variables and feature scaling.

Dimensionality reduction is applied using Principal Component Analysis (PCA) to visualize and analyze high-dimensional patterns in 2D and 3D space.

Three clustering algorithms are implemented: K-Means, Gaussian Mixture Models, and DBSCAN. Clustering performance is evaluated using the Silhouette Score. The ranking of the models based on average silhouette scores is as follows: K-Means performed best, followed by Gaussian Mixture, with DBSCAN performing poorly on this dataset.

Visualizations include pairwise PCA plots, algorithm comparison scatter plots, and decision boundary illustrations. The project also includes EDA insights such as distributions of age, income, and spending score, as well as the average cluster-wise feature values.

This project helps understand clustering, unsupervised learning techniques, dimensionality reduction, and how to interpret model output to make business decisions such as identifying high-value or low-engagement customer groups.
