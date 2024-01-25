Customer Segmentation Using K-Means Clustering

Objective: The objective of this project is to segment customers based on their attributes using the K-Means clustering algorithm.

Key Steps:

Importing Libraries: Necessary libraries such as Pandas, NumPy, Scikit-learn, and Matplotlib are imported to perform data manipulation, clustering, and visualization tasks.

Loading Data: The project begins by loading a CSV file containing customer data into a Pandas DataFrame.

Data Preprocessing: Since the dataset includes a categorical variable "Address," which is not suitable for the K-Means algorithm, it's dropped from the DataFrame.

K-Means Clustering: The K-Means clustering algorithm is applied to the preprocessed data to group customers into a predefined number of clusters (in this case, 3 clusters).

Assigning Labels: Cluster labels obtained from the K-Means algorithm are assigned to each row in the DataFrame.

Centroid Analysis: The centroid values of each cluster are computed by averaging the features within each cluster.

Data Visualization: Two types of visualizations are created to explore the customer segmentation:

Scatter plot of age vs. income, where each point is colored according to its cluster label.
3D scatter plot of education, age, and income, with points colored by cluster label.
