# Mall Customer Segmentation using K-Means Clustering 🛒

## Project Goal
The goal of this project is to segment mall customers into distinct groups based on their age, annual income, and spending habits. This allows the marketing team to create targeted campaigns for each customer segment.

---

## Dataset
This project uses a popular dataset from Kaggle containing information on 200 mall customers. The key features used for clustering are:
* `Age`
* `Annual Income (k$)`
* `Spending Score (1-100)`

**Link:** `[You can add the link to the dataset here]`

---

## Methodology ⚙️

1.  **Exploratory Data Analysis (EDA):** Loaded and inspected the dataset to understand its structure and features.
2.  **Feature Scaling:** Applied `StandardScaler` to the numerical features to ensure that each feature contributes equally to the distance calculations in the K-Means algorithm.
3.  **Finding Optimal K:** Used the **Elbow Method** to determine the optimal number of clusters for the data, which was found to be **K=5**.
4.  **Clustering:** Trained a `KMeans` model with K=5 on the scaled data to group the customers into 5 distinct segments.
5.  **Cluster Interpretation:** Analyzed the feature averages for each cluster to create meaningful business personas.

---

## Results & Insights 💡

The analysis resulted in 5 distinct customer segments:

* **Cluster 0:** `[Describe your interpretation for Cluster 0 here]`
* **Cluster 1:** `[Describe your interpretation for Cluster 1 here]`
* **Cluster 2:** `[Describe your interpretation for Cluster 2 here]`
* **Cluster 3:** `[Describe your interpretation for Cluster 3 here]`
* **Cluster 4:** `[Describe your interpretation for Cluster 4 here]`

This segmentation enables the business to move from a one-size-fits-all marketing approach to a targeted strategy, potentially increasing engagement and sales.
