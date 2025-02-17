# Customer Segmentation Clustering

## Overview
This repository demonstrates a customer segmentation analysis using **PCA (Principal Component Analysis)** and **K-Means Clustering**. Customer segmentation is a critical process for understanding different groups of customers based on their behavior, preferences, or other relevant features. By clustering customers, businesses can tailor marketing strategies, improve customer satisfaction, and increase overall efficiency.

---

## Features
1. **Data Preprocessing**:
   - Data normalization using StandardScaler to ensure all features contribute equally.
2. **Dimensionality Reduction**:
   - PCA is applied to reduce the dimensionality of the dataset while retaining the most important information.
3. **Clustering**:
   - K-Means algorithm is used to segment customers into distinct groups.
4. **Visualization**:
   - Individual Factor Map and Variable Factor Map visualizations are used to interpret PCA.
   - Cluster visualization using PCA components for an intuitive understanding of groupings.
5. **Cluster Analysis**:
   - Centroids are analyzed to identify the dominant features in each cluster.
   - Silhouette Score is calculated to evaluate clustering performance.

---

## Installation
To run this project locally, ensure you have Python installed. Clone this repository and install the required dependencies:

```bash
# Clone the repository
git clone https://github.com/AmriDomas/customer-segmentation-clustering.git

# Navigate to the directory
cd customer-segmentation-clustering

# Install dependencies
pip install -r requirements.txt
```

---

## Usage
1. **Prepare Your Data**:
   - Replace the sample data with your customer dataset in the provided script.
2. **Run the Analysis**:
   - Execute the script to preprocess, perform PCA, and apply clustering.

```bash
python customer_segmentation_clustering.py
```
3. **View Results**:
   - Check the visualizations and cluster statistics generated by the script.

---

## Visualizations
### 1. Individual Factor Map (PCA)
Illustrates the distribution of customers in the reduced PCA space, highlighting the separation between clusters.

### 2. Variable Factor Map (PCA)
Shows the contribution of original features to the principal components, helping identify the most significant variables.

### 3. Cluster Visualization
Plots clusters in the PCA space, providing a clear understanding of customer groupings.

### 4. Silhouette Analysis
Evaluates the quality of clustering by measuring the separation between clusters.

---

## Key Metrics
- **Explained Variance Ratio**: Percentage of data variance captured by each principal component.
- **Silhouette Score**: Measures the compactness and separation of clusters.

---

## Example Results
### Cluster Analysis:
Each cluster represents a unique segment of customers:
1. **Cluster 0**: Customers with high engagement in `Income` and `purchase`.
2. **Cluster 1**: Dominated by `Income` and `purchase`, indicating specific preferences.
3. **Cluster 2**: Segmented by strong influence of `Income` and `purchase``.
4. Centroid value all cluster has different

### Visual Insights:
- PCA reduced data complexity, making clustering more efficient.
- K-Means effectively grouped customers with similar patterns.

---

## Contribution
Feel free to contribute to this project! If you encounter any issues or have suggestions for improvement, create a pull request or open an issue.

---

## Acknowledgments
- **Scikit-learn**: For providing robust machine learning tools.
- **Matplotlib and Seaborn**: For data visualization.
- **Pandas and NumPy**: For efficient data handling.

---

### Author
**Your Name**  
Data Scientist | [LinkedIn](https://www.linkedin.com/in/muh-amri-sidiq) | [GitHub](https://github.com/AmriDomas)

