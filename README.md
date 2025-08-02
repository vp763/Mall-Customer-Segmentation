# Mall Customer Segmentation using K-Means Clustering 🛒

## Project Goal
The goal of this project is to segment mall customers into distinct groups based on their age, annual income, and spending habits. This allows the marketing team to create targeted campaigns for each customer segment.

---

## Dataset
This project uses a popular dataset from Kaggle containing information on 200 mall customers. The key features used for clustering are:
* `Age`
* `Annual Income (k$)`
* `Spending Score (1-100)`

**Link:** `(https://raw.githubusercontent.com/vp763/Mall-Customer-Segmentation/refs/heads/main/Mall_Customers.csv)`

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

* **Cluster 0:** `Older customers (average age 53) with a solid average income but a very low spending score. They earn well but don't spend much.`
* **Cluster 1:** `Younger customers (average age 28) with an average income and a good spending score. This group represents the general, active shoppers.`
* **Cluster 2:** `Middle-aged customers (average age 48) with an average income but a low spending score, similar to the senior group.`
* **Cluster 3:** `The ideal customers. Middle-aged (average age 33) with a very high income and a very high spending score. Marketing efforts should be focused on this group.`
* **Cluster 4:** `Very young customers (average age 24) with a slightly lower-than-average income but a decent spending score. They are the future high-spenders.`

This segmentation enables the business to move from a one-size-fits-all marketing approach to a targeted strategy, potentially increasing engagement and sales.
