
# Customer Segmentation for Target Marketing Using Machine Learning

## Overview
This project performs customer segmentation for an automobile company by analyzing customer data such as annual income, spending behavior, profession, and demographics. The objective is to group customers into distinct segments for targeted marketing, utilizing machine learning algorithms to identify patterns and clusters in the data.

## Table of Contents
- [Project Structure](#project-structure)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Algorithms Used](#algorithms-used)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Clustering Methods](#clustering-methods)
- [Evaluation](#evaluation)
- [Visualizations](#visualizations)
- [Conclusion](#conclusion)
- [License](#license)

## Dataset
The project uses a customer dataset with the following features:
- `Gender`
- `Age`
- `Annual Income ($)`
- `Spending Score (1-100)`
- `Profession`

## Requirements
The following Python packages are required to run the project:
- pandas
- numpy
- scikit-learn
- seaborn
- matplotlib
- plotly
- scipy

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Jilpadalia/CustSeg_ML.git
   cd CustSeg_ML
   ```
2. Run the Jupyter notebook `CustSeg_ML.ipynb` to view analysis and visualizations.

## Algorithms Used
The project implements the following clustering algorithms:
- **KMeans Clustering**
- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)**
- **Gaussian Mixture Models (GMM)**
- **Agglomerative Hierarchical Clustering**

## Exploratory Data Analysis
Initial analysis includes:
- Gender distribution
- Profession distribution
- Age distribution across gender and profession
- Correlation analysis using heatmaps

## Clustering Methods
1. **KMeans Clustering**:
   - Performed clustering with varying `k` values.
   - Used the elbow method to determine the optimal number of clusters.

2. **DBSCAN**:
   - Applied to detect clusters of varying shapes and sizes, with parameters `eps` and `min_samples` tuned for optimal performance.

3. **Gaussian Mixture Models (GMM)**:
   - Implemented to handle clusters with varying covariance structures, providing a probabilistic approach to clustering.

4. **Agglomerative Hierarchical Clustering**:
   - Used to generate a dendrogram to visualize the clustering hierarchy.

## Evaluation
- **Silhouette Score**: Evaluated the performance of KMeans and GMM clustering algorithms.
- **WCSS (Within-Cluster Sum of Squares)**: Applied to KMeans clustering to determine the optimal number of clusters.

## Visualizations
- Pie charts for gender and profession distribution.
- Box plots to show age and income distribution across various demographics.
- Scatter plots to visualize customer clusters based on spending and income.
- Dendrogram for hierarchical clustering.

## Conclusion
This project demonstrates the use of various machine learning techniques to segment customers into different clusters based on spending behavior and income. These insights can be used for targeted marketing strategies.
