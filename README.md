# KMeans_clustering

## Description
This project implements a custom K-Means clustering algorithm in Python, designed to partition a given set of data points into specified clusters. The implementation allows for user-defined parameters such as the number of clusters, outlier detection radius, data generation ranges, and initial seed points for centroids. This project demonstrates the K-Means clustering process through iterative centroid updates until convergence is achieved.

## Features
- Custom K-Means Algorithm: Implements clustering with user-defined parameters.
- Outlier Detection: Identifies outliers based on a specified distance threshold.
- Dynamic Data Generation: Generates random data points within a user-specified range.
- User-defined Initial Seeds: Supports user input for initial centroid locations.
- Cycle Tracking and Convergence Reporting: Provides cycle-by-cycle tracking of centroid changes and cluster membership.

## Running the Model
Provide inputs as prompted:
- Number of clusters: Define the number of desired clusters.
- Radius for outlier detection: Specify a distance threshold for identifying outliers.
- Data range: Define the minimum and maximum range for data point generation.
- Number of data points: Specify the number of points to generate.
- Initial seed points (optional): Enter initial centroid positions or leave blank for random initialization.
- The algorithm will generate data points and perform K-Means clustering iteratively.
- View detailed output per cycle, including:
  - Centroid positions
  - Cluster assignments
  - Outlier detection and reporting
  - Convergence status

## Technologies Used
- Python: Core programming language for implementation.
- Jupyter Notebook: Interactive environment for code execution and visualization.
- numpy: Used for efficient numerical operations and data handling.

## Contributing
Contributions are welcome! If you have suggestions, find a bug, or want to enhance the project, please open an issue or submit a pull request.
