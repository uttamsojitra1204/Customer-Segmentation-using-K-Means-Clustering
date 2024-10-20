# Customer-Segmentation-using-K-Means-Clustering

=> This project performs customer segmentation using the K-Means clustering algorithm on a dataset of mall customers. The segmentation is based on two features: Annual Income and Spending Score. The result is visualized with scatter plots to show the identified clusters.

=> Project Structure

1. Data Collection and Analysis:
- The dataset (Mall_Customers.csv) is loaded using Pandas.
- It contains 200 records with the following columns:
  - CustomerID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)

2. Data Preprocessing:
- The features Annual Income and Spending Score are extracted for clustering.
- Basic checks for null values and summary statistics are performed to understand the data.

3. K-Means Clustering:
- The Elbow method is used to determine the optimal number of clusters by plotting the Within-Cluster Sum of Squares (WCSS) against different numbers of clusters.
- K-Means is applied with the optimal number of clusters (5 in this case).
- The data points are assigned to different clusters using the fit_predict function.

4. Visualization:
- Scatter plots are generated to visualize the clusters and their centroids.
- Each cluster is displayed with a unique color to make the visualization clearer.

=> Conclusion
- This project provides an introduction to customer segmentation using K-Means clustering. The elbow method helps in selecting the optimal number of clusters, and visualizations make it easy to interpret the results. This analysis could be extended to recommend targeted marketing strategies based on the identified customer groups.

=> Contact Us

1. Email: uttamsojitra.ds@gmail.com

2. LinkedIn: https://www.linkedin.com/in/uttam-sojitra-6aa781236/

Feel free to reach out for any collaboration, job opportunities, or project discussions!
