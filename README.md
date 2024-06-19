# Wholesale Data Analysis Project

## Project Overview
This project involves the application of unsupervised learning techniques on the Wholesale Data dataset to identify patterns and group similar data points. The main tasks include exploratory data analysis (EDA), data pre-processing, KMeans clustering, hierarchical clustering, and Principal Component Analysis (PCA).

## Instructions
1. Clone the repository.
2. Install the required packages using `pip install -r requirements.txt`.
3. Run the Jupyter notebook to execute the analysis.

## Summary of Findings
### EDA
- **Data Distribution and Outliers**: Insights were gained on the distribution of each feature, with outliers being detected and handled appropriately.
- **Correlation Analysis**: A correlation heatmap revealed significant correlations between certain features, aiding in feature selection.

### Data Pre-processing
- **Handling Missing Values and Duplicates**: Missing values were imputed using the median, and duplicate rows were removed.
- **Outlier Detection and Imputation**: Outliers were detected and imputed with the median to ensure robust clustering.
- **Feature Engineering**: A new feature `Total_Bought` was created to capture the total spending across all product categories.
- **Feature Encoding and Scaling**: Categorical variables were encoded using one-hot encoding, and all features were scaled for better clustering performance.

### Clustering
- **KMeans Clustering**:
  - **Optimal Number of Clusters**: The Elbow Method identified the optimal number of clusters as \( k = 3 \).
  - **Cluster Analysis**: The clusters were analyzed using pair plots, revealing distinct groupings based on customer purchasing patterns.
  
- **Hierarchical Clustering**:
  - **Dendrogram Analysis**: The dendrogram suggested the presence of two main clusters.
  - **Cluster Visualization**: PCA was used to reduce dimensionality and visualize the clusters, confirming well-separated groups.

### PCA
- **Variance Explanation**: The first two principal components explained a significant portion of the variance in the data, aiding in effective visualization of clusters.

## Business Applications
- **Customer Segmentation**: The identified customer segments can help in targeted marketing strategies, allowing businesses to tailor their offerings to different customer groups.
- **Inventory Management**: Insights from clustering can optimize inventory levels based on customer purchasing patterns, reducing wastage and improving stock availability.

## Files
- `Wholesale_Data.csv`: Dataset used for analysis.
- `Analysis.ipynb`: Jupyter notebook containing the analysis code.
- `README.md`: Project documentation.

