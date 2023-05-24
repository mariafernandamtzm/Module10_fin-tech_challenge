# Module10_fin-tech_challenge

Cryptocurrency Clustering with K-Means and PCA
This repository contains code and data for performing clustering analysis on cryptocurrency data using the K-Means algorithm and Principal Component Analysis (PCA).

Data
The cryptocurrency data used for the analysis is stored in the file crypto_data.csv. It includes various features such as the price change percentage over 24 hours and 7 days, market capitalization, and trading volume for different cryptocurrencies.

Code
The main code file for the analysis is cryptocurrency_clustering.ipynb, which is a Jupyter Notebook written in Python. The notebook includes the following sections:

Data Preprocessing: This section focuses on loading the data, cleaning it, and preparing it for further analysis. It includes steps such as removing missing values, scaling the data, and encoding categorical variables.

Clustering with K-Means: This section applies the K-Means algorithm to cluster the cryptocurrencies based on the selected features. It includes finding the optimal number of clusters using the elbow method and visualizing the results using scatter plots.

Clustering with PCA: This section utilizes Principal Component Analysis (PCA) to reduce the dimensionality of the data and then applies K-Means clustering on the reduced features. It includes steps such as creating a PCA model, determining the explained variance, and visualizing the results.

Visualizing and Comparing the Results: This section compares the clustering analysis results using the original data and the PCA data. It includes composite plots to contrast the elbow curves and scatter plots of the clusters.

Libraries Used
The analysis makes use of the following Python libraries:

pandas: for data manipulation and analysis
scikit-learn: for implementing the K-Means algorithm and PCA
hvPlot: for interactive plotting
Holoviews: for creating composite plots
Instructions
To run the code and reproduce the analysis:

Clone this repository to your local machine.

Ensure you have the necessary dependencies installed by running pip install -r requirements.txt.

Open the cryptocurrency_clustering.ipynb notebook in Jupyter Notebook or JupyterLab.

Follow the step-by-step instructions in the notebook to execute the code cells and analyze the results.

Note: Make sure to have Python 3.x and the required libraries installed for a smooth execution.

Feel free to explore and modify the code as needed to further customize the analysis or apply it to different datasets.

Happy clustering!





