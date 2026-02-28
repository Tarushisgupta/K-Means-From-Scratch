# 🚀 K-Means Clustering From Scratch (Without sklearn)

## 📌 Project Overview

This project implements the **K-Means clustering algorithm entirely from
scratch** using NumPy, without relying on sklearn.

The objective of this project was to deeply understand the mathematical
and computational foundation of K-Means, including:

-   Centroid initialization\
-   Euclidean distance computation\
-   Cluster assignment\
-   Centroid updates\
-   Convergence criteria\
-   Cluster visualization

------------------------------------------------------------------------

## 🧠 How the Algorithm Works

1.  Randomly initialize **K centroids**
2.  Compute Euclidean distance between each data point and centroids
3.  Assign each point to its nearest centroid
4.  Update centroids as the mean of assigned points
5.  Repeat until centroid movement is smaller than a defined tolerance

------------------------------------------------------------------------

## 📊 Visualization

The final clusters are visualized using Matplotlib:

-   Data points are color-coded by cluster
-   Centroids are clearly marked
-   Clean 2D representation of cluster separation

Add your generated output image inside the `images/` folder and display
it like this:

![Clustering Result](images/clustering_result.png)

------------------------------------------------------------------------

## ⚙️ Tech Stack

-   Python\
-   NumPy\
-   Matplotlib

------------------------------------------------------------------------

## 📈 Key Learnings

-   Efficient vectorized distance computation using NumPy\
-   Importance of centroid stability for convergence\
-   Impact of initialization on final clusters\
-   Stronger understanding of unsupervised learning fundamentals

------------------------------------------------------------------------

## 🎯 Why This Project Matters

While high-level libraries make implementation easy, understanding how
clustering algorithms work internally builds deeper intuition and
stronger problem-solving skills for real-world machine learning tasks.

