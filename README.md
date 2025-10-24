K-Means Clustering with Iris Dataset (Petal Features)
This repository contains a Jupyter notebook demonstrating K-Means clustering applied to the Iris dataset, focusing on the petal length and petal width features.

Project Summary
The goal of this project was to perform K-Means clustering on the Iris dataset using only the 'petal length (cm)' and 'petal width (cm)' features to identify natural groupings within the data. The process involved loading and preparing the data, scaling the features, determining the optimal number of clusters using the elbow method and silhouette analysis, applying the K-Means algorithm, and visualizing the resulting clusters.

Analysis and Findings
The Iris dataset was loaded and prepared, isolating the 'petal length (cm)' and 'petal width (cm)' features.
MinMaxScaler was applied to the selected features to ensure equal contribution during clustering.
Both the elbow method and silhouette analysis were used to evaluate the optimal number of clusters. The silhouette analysis indicated that k=2 was the most suitable number of clusters for this specific feature subset, yielding the highest silhouette score (0.7417).
K-Means clustering was performed with k=2.
The visualization of the clusters clearly shows two distinct groups based on petal length and width, aligning with the findings from the optimal k determination.
Next Steps
Explore K-Means clustering with k=3 to see how well the clusters align with the actual three species in the Iris dataset.
Evaluate the clustering performance with k=3 using metrics such as Adjusted Rand Index or Homogeneity Score, comparing them to the known species labels.
Consider incorporating other features from the Iris dataset or applying different clustering algorithms to compare results.
How to Run the Notebook
Clone this repository.
Ensure you have the necessary libraries installed (e.g., pandas, scikit-learn, matplotlib). You can install them using pip: pip install pandas scikit-learn matplotlib
Open the Jupyter notebook (your_notebook_name.ipynb) in a Jupyter environment (like Jupyter Notebook, JupyterLab, or Google Colab).
Run the cells sequentially to execute the analysis
