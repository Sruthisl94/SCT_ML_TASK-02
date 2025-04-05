# 🛍️ Mall Customer Segmentation Using K-Means Clustering

This project demonstrates how to use **K-Means Clustering**, an unsupervised machine learning algorithm, to segment customers in a mall based on their demographic and spending data. The goal is to help businesses understand different customer groups and make informed marketing decisions.


## 📌 Problem Statement

Retail businesses often struggle with understanding and targeting their customers effectively. By segmenting customers into distinct groups based on their behavior and attributes, companies can:
- Improve customer experience
- Personalize marketing efforts
- Increase revenue through targeted offers

---

## 📂 Dataset

The dataset contains the following features:

- **CustomerID** – Unique ID for each customer
- **Gender** – Male or Female
- **Age** – Customer's age
- **Annual Income (k$)** – Annual income of the customer in thousand dollars
- **Spending Score (1-100)** – Score assigned based on customer behavior and spending nature

📁 Dataset Source: *Mall_Customers.csv* (available on Kaggle or included in this repo)

---

## 🧠 Methodology

### 1. **Data Preprocessing**
- Handled missing values (if any)
- Scaled features for better clustering performance

### 2. **Exploratory Data Analysis**
- Distribution of  income and spending score
- Relationship between income and spending
- Correlation matrix

### 3. **K-Means Clustering**
- Applied the **Elbow Method** to determine the optimal number of clusters
- Implemented K-Means using `sklearn`
- Visualized the customer clusters using scatter plots and color-coded groups

### 4. **Cluster Interpretation**
Each cluster was analyzed based on income and spending behavior to label customer types such as:
- High-value customers
- Low-income high spenders
- Moderate income moderate spenders, etc.

---

## 🔧 Tech Stack

- **Language:** Python 3  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Algorithms:** K-Means Clustering, Elbow Method, Silhouette Score

---

## 📊 Key Insights

- Identified 5 distinct customer segments
- Found a group of high-income but low-spending customers — a potential target for engagement
- Helped visualize and understand mall customer behavior more clearly

---
