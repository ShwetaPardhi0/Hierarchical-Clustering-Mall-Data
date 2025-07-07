# 📊 Mall Customer Segmentation using Hierarchical Clustering

This project applies **Hierarchical Clustering** to a mall customer dataset to segment customers into distinct groups based on their annual income and spending behavior. It's an unsupervised machine learning task aimed at understanding customer profiles to improve marketing strategies.

---

## 📁 Dataset Overview

The dataset `Mall_Customers.csv` contains 200 records with the following features:

- `CustomerID`: Unique ID assigned to each customer
- `Gender`: Gender of the customer
- `Age`: Age of the customer
- `Annual Income (k$)`: Annual income of the customer in $1000s
- `Spending Score (1–100)`: Score assigned by the mall based on customer behavior and spending nature

---

## 🎯 Objectives

- Explore and visualize customer data
- Preprocess and standardize features
- Use **Dendrogram** to determine the optimal number of clusters
- Apply **Agglomerative Hierarchical Clustering**
- Visualize and interpret customer clusters

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- Jupyter Notebook
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scipy.cluster.hierarchy`
- `sklearn.cluster.AgglomerativeClustering`

---

## 📈 Visualizations

- Heatmaps and pairplots for EDA
- Dendrogram to determine cluster count
- 2D scatter plots to visualize final clusters

---

## 📂 File Structure

├── Hierarchical Clustering.ipynb # Main notebook

├── Mall_Customers.csv # Dataset

├── README.md # Project overview
