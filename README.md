# Customer Segmentation

## Overview

This project performs customer segmentation using unsupervised machine learning techniques to group customers into distinct segments based on their behavioral and demographic attributes. It helps businesses tailor marketing strategies, improve customer experience, and drive targeted promotions.
![Clustering](https://github.com/user-attachments/assets/0f56ae65-7d77-4b47-bf5b-1948742e4119)

## Features

* **Data Exploration**: Conducted exploratory data analysis to understand customer attributes and identify patterns.
* **Preprocessing**: Handled missing values, scaled numerical features, and encoded categorical variables.
* **Segmentation Techniques**:

  * **K-Means Clustering**: Grouped customers into clusters based on feature similarity.
  * **Hierarchical Clustering**: Validated cluster structures and provided dendrogram visualizations.
* **Cluster Evaluation**:

  * **Silhouette Score**: Assessed the quality of clustering.
  * **Elbow Method**: Determined the optimal number of clusters for K-Means.
* **Visualization**:

  * **PCA/T-SNE**: Reduced dimensionality for 2D/3D scatter plots of clusters.
  * **Cluster Profiles**: Analyzed segment characteristics through summary statistics and bar plots.

## Files

* `Customer_Segmentation.ipynb`: Jupyter notebook with the full workflow, from data loading and preprocessing to clustering, evaluation, and visualization.
* `README.md`: This documentation file.


## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/akhilesh360/Customer_Segmentation.git
   cd Customer_Segmentation
   ```
2. (Optional) Create and activate a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\\Scripts\\activate
   ```
3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Launch Jupyter Notebook:

   ```bash
   jupyter notebook Customer_Segmentation.ipynb
   ```
2. Run all cells to execute the segmentation analysis and review visualizations.

**Clustering Results**


These insights enable the company to target customers more effectively based on their age and spending behavior, driving the design of efficient marketing strategies and personalized campaigns.

![Clusters](https://github.com/user-attachments/assets/893faab6-d695-41dd-9b37-8db5f6af8612)

**Output Insights**

The 3D scatter plot visualizes the clustering results by plotting customers based on their spending behavior, annual income, and age. Each cluster is represented by a distinct color, making it easy to identify key customer segments. The spatial distribution of the clusters shows how different age groups and spending patterns correlate


## Conclusions

* Identified meaningful customer segments that can be leveraged for targeted marketing.
* Provided actionable insights into segment sizes, buying patterns, and demographic profiles.

## Author

Created by Sai Akhilesh.



