Customer Segmentation using Clustering
Project Overview

This project focuses on Unsupervised Machine Learning (Clustering) to group customers based on their purchasing behavior and demographic features. The goal is to identify meaningful customer segments using clustering algorithms such as K-Means and DBSCAN.

Dataset Information
Dataset Name: Mall Customer Segmentation Dataset
Source: Kaggle
Link: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
Records: 200
Features: 5
Feature Description:
CustomerID → Unique ID for each customer
Gender → Male / Female
Age → Age of customer
Annual Income (k$) → Yearly income
Spending Score (1-100) → Customer spending behavior score
Objective

To segment customers into different groups based on:

Age
Income
Spending behavior

This helps businesses understand customer patterns and improve marketing strategies.

Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
KaggleHub / Google Colab
Data Preprocessing
Loaded dataset using KaggleHub
Checked for missing values
Encoded categorical variable (Gender)
Applied feature scaling using StandardScaler
Algorithms Used
1️K-Means Clustering (Mandatory)
Used Elbow Method to find optimal number of clusters
Applied KMeans with optimal K value
Evaluated using Silhouette Score
Evaluation Metrics
Silhouette Score used to measure clustering quality
Cluster visualization used for interpretation
Visualizations
Elbow Method Graph (WCSS vs Clusters)
2D Cluster Visualization (Income vs Spending Score)

Project Structure
Clustering-Project/
│
├── clustering.ipynb
├── Mall_Customers.csv
├── clustered_output.csv
├── README.md
└── plots/
    ├── elbow_method.png
    ├── kmeans_clusters.png
    
How to Run the Project
Step 1: Open Google Colab

Use Google Colab

Step 2: Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn kagglehub
Step 3: Run notebook
Load dataset using KaggleHub
Run all preprocessing steps
Train KMeans model
Visualize clusters
Key Results
Successfully grouped customers into meaningful clusters
Identified high-value customers using spending score
KMeans gave clear segmentation

Conclusion

This project demonstrates how unsupervised learning can be used to discover hidden patterns in customer data without labeled outputs. It is useful for:

Marketing strategy
Customer targeting
Business decision-making

📎 Dataset Link

https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
