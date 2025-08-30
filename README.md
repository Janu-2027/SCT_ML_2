🛒 Customer Segmentation using K-Means Clustering
This project performs customer segmentation using the Mall Customers dataset.
By applying the K-Means clustering algorithm, customers are grouped based on their Annual Income and Spending Score to identify distinct customer segments.

📂 Dataset
The dataset used is Mall_Customers.csv, which contains customer details including:

CustomerID
Gender
Age
Annual Income (k$)
Spending Score (1-100)
⚙️ Steps in the Project
1. Import Libraries
Essential Python libraries such as pandas, matplotlib, seaborn, sklearn are used.

2. Load Dataset
Load the Mall Customers dataset using pandas.

3. Select Features
Select features for clustering:

Annual Income (k$)
Spending Score (1-100)
4. Feature Scaling
Standardize the selected features using StandardScaler to ensure better clustering.

5. Elbow Method
Use the Elbow Method to determine the optimal number of clusters (k).
This involves plotting WCSS (Within-Cluster Sum of Squares) against cluster numbers.

6. Apply K-Means Clustering
Train K-Means with the chosen number of clusters (k=5 in this project).

7. Visualize Clusters
Plot clusters in a 2D scatter plot with different colors and show cluster centroids.

8. Save Results
The final dataset with cluster labels is saved as:
