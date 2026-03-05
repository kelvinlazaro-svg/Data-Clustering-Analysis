# Data-Clustering-Analysis
An Unsupervised Machine Learning project using K-Means Clustering to segment student performance based on test scores and assignments
Student Performance Segmentation using K-Means
This project applies Unsupervised Machine Learning to categorize students based on their academic results. By using clustering techniques, we can identify different groups of students who share similar performance patterns in tests and assignments.

⚠️ Project Overview
The goal of this analysis is to perform student segmentation based on four key features:

TEST 1

ASS1 (Assignment 1)

TEST 2

TOTAL SCORE

🛠️ Tech Stack & Libraries
Python (Main language)

Pandas & NumPy (Data manipulation)

Matplotlib & Seaborn (Data visualization)

Scikit-Learn (Machine Learning implementation - KMeans & StandardScaler)

🚀 Key Steps in the Notebook
Data Preprocessing: Handled missing values in the ASS1 column using the mean strategy.

Feature Scaling: Applied StandardScaler to normalize the scores for better clustering performance.

Finding Optimal Clusters: Used the Elbow Method (WCSS) to determine that 3 to 6 clusters are ideal for this dataset.

Clustering: Implemented K-Means Clustering and evaluated the model using a Silhouette Score of 0.35.

Insights: Created cluster summaries to show the average performance of each group.
