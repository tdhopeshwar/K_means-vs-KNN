# 📊 Clustering and Classification with K-Means, K-Means++ and KNN

This project demonstrates unsupervised and supervised learning techniques by implementing K-Means, K-Means++, and K-Nearest Neighbors (KNN) from scratch using Python. It focuses on clustering multi-dimensional data and classifying new data points based on the generated clusters.

## 🔍 Project Overview
✅ Objectives:
* Perform clustering on unlabeled data using K-Means and K-Means++.

* Compare convergence behavior and cluster quality of K-Means vs K-Means++.

* Assign class labels to clustered data points.

* Use KNN to classify new data based on labeled clusters.

# ⚙️ Methods Implemented
## 1. K-Means Clustering

* Random initialization of centroids.

* Iterative reassignment of points to nearest centroids.

* Convergence is checked based on centroid stability.

* Visualized centroid movement and cluster formation at each iteration.

## 2. K-Means++ Clustering

* Improved centroid initialization using distance-based probabilistic selection.

* Achieves faster and more accurate convergence than standard K-Means.

* Clear separation between clusters observed within fewer iterations.

## 3. K-Nearest Neighbors (KNN) Classification

After assigning cluster labels using K-Means++, the labeled dataset is used to classify new data points based on nearest neighbors using Euclidean distance.

## 📈 Visualizations

* Step-by-step visual plots for centroid initialization and clustering progression.

* Comparison of iterations across K-Means and K-Means++.

* Cluster assignments clearly color-coded in 2D plots using features X1 and X2.

## 🧠 Key Learnings

* K-Means++ provides better and more stable initial centroids, reducing convergence time and improving cluster quality.

* Manual implementation reinforces understanding of distance metrics, label assignment, and convergence logic.

* Visualizations help trace the algorithm’s learning process over time.

## 🚀 Future Improvements

* Extend KNN implementation to evaluate performance (e.g., accuracy, confusion matrix).

* Add elbow method or silhouette score to determine optimal k.

* Introduce dimensionality reduction (e.g., PCA) for high-dimensional data.

## 📌 Requirements

*Python 3.x

* Libraries: numpy, pandas, matplotlib




