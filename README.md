# CryptoClustering:
Began by importing the dependencies and libraries.
Created a DataFrame in order to plot and prepare the data.
Used 'StandardScaler()' to create an array and 'normalize' data from CSV.
Created DataFrame with the scaled data.
Found best value for 'k' using the Original Data ('scaled_crypt_df').
Plotted a line chart with all the inertia values computed with the different values of k to visually identify the optimal value for k (elbow_plot).
Answer the following question:
-Question: What is the best value for k?
-Answer:: k = 4; The optimal k is the one that maximizes the gap between the observed and expected inertia.
Clustered the Cryptocurrencies with K-means Using the Original Data.
Created a scatter plot using hvPlot by setting the Cluster Cryptocurrencies with K-means Using the Original Data.
Optimized the Clusters with Principal Component Analysis.
Answer the following question:¶
-Question: What is the total explained variance of the three principal components?
-Answer:: Total = (0.3719856 + 0.34700813 + 0.17603793) = 0.89503166; approximately 90%.
Found the Best Value for k Using the PCA Data:
Answer the following questions:
-Question: What is the best value for k when using the PCA data?
-Answer:: k=3; the optimal k is typically the value corresponding to this elbow point.
-Question: Does it differ from the best k value found using the original data?
-Answer: : Yes.
Clustered Cryptocurrencies with K-means Using the PCA Data ('pca_predictons_plot').
Visualized and compared the results by comparing:  'elbow_plot' and 'elbow2_plot', and also 'scaled_crypt_pred_plot' and 'pca_predictions_plot'.
Answer the following question:
-Question: After visually analyzing the cluster analysis results, what is the impact of using fewer features to cluster the data using K-Means?
-Answer:: Inertia is reduced, resulted in more precise clustering in the'PCA'-plot.
