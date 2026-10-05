# Big Bazaar Customer Segmentation Using Machine Learning

## Mini-MST Project – UCS321

### Project Overview

Big Bazaar aims to segment its customers into distinct groups to optimize promotional strategies and improve sales.

This project develops a Python-based machine learning solution using **K-Means Clustering** to identify different customer segments based on customer characteristics such as:

- Age
- Annual Income
- Spending Score

The project includes data cleaning, preprocessing, exploratory data analysis, clustering, visualization, and performance evaluation.

---

## Problem Statement

Big Bazaar wants to understand its customers and divide them into meaningful groups based on their characteristics and spending behavior.

Customer segmentation can help the company design targeted promotional strategies and improve sales by understanding the behavior of different customer groups.

---

## Objectives

The main objectives of this project are:

1. Load and understand the customer dataset.
2. Clean and preprocess the data.
3. Perform exploratory data analysis and visualization.
4. Select relevant features for customer segmentation.
5. Apply K-Means clustering.
6. Determine a suitable number of customer clusters.
7. Evaluate the clustering performance.
8. Analyze the characteristics of each customer segment.
9. Suggest suitable business and promotional strategies for different customer groups.

---

## Dataset

The project uses the **Mall Customers dataset**.

The dataset contains the following main attributes:

| Feature | Description |
|---|---|
| CustomerID | Unique identification number of the customer |
| Genre | Gender of the customer |
| Age | Age of the customer |
| Annual Income (k$) | Annual income of the customer in thousands of dollars |
| Spending Score (1-100) | Spending score assigned to the customer |

### Selected Features

For K-Means clustering, the following numerical features are used:

- Age
- Annual Income (k$)
- Spending Score (1-100)

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- VS Code

---

## Machine Learning Technique

### K-Means Clustering

K-Means is an unsupervised machine learning algorithm used to divide data points into groups called clusters.

In this project, K-Means is used to group Big Bazaar customers according to similarities in their:

- Age
- Annual Income
- Spending Score

The algorithm assigns customers to clusters based on their distance from cluster centroids.

---

## Project Workflow

```text
Customer Dataset
       ↓
Data Cleaning
       ↓
Data Pre-processing
       ↓
Exploratory Data Analysis
       ↓
Feature Selection
       ↓
Feature Scaling
       ↓
K-Means Clustering
       ↓
Determine Optimal Number of Clusters
       ↓
Cluster Evaluation
       ↓
Customer Segment Analysis
       ↓
Visualization
       ↓
Business Recommendations