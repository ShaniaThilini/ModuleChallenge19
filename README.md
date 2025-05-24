# ModuleChallenge19
This project uses K-Means clustering to group cryptocurrencies based on their price change percentages over various timeframes. The process involves:

Scaling the data using StandardScaler

Applying the Elbow Method to find the best number of clusters (k)

Clustering the data using K-Means

Reducing dimensions with PCA for better visualization

Comparing results with and without PCA

🔧 Tools Used
Python

Pandas

Scikit-learn

hvPlot

Matplotlib

✅ Key Finding
The optimal number of clusters (k) is 4 in both the original and PCA-reduced datasets. PCA retained about 89.5% of the original data’s information, making it effective for clustering with fewer features.

