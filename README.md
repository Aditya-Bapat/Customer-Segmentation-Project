# Customer-Segmentation-Project

# 🧠 Customer Segmentation Project

This project uses **KMeans Clustering** to group mall customers based on key demographic and behavioral factors such as **Age**, **Annual Income**, and **Spending Score**. It helps identify distinct customer segments that can be used for **targeted marketing**, **loyalty programs**, and **business decision-making**.

---

## 📌 Objective

To segment customers into meaningful groups using unsupervised learning (KMeans), enabling businesses to understand and target different types of customers more effectively.

---

## 🗃️ Dataset

**Mall Customers Dataset**  
- Source: [Kaggle](https://www.kaggle.com/datasets/abdallahwagih/mall-customers-segmentation)
- Size: 200+ records  
- Features: `CustomerID`, `Gender`, `Age`, `Annual Income (k$)`, `Spending Score (1–100)`

---

## ⚙️ Technologies Used

- Python  
- pandas, seaborn, matplotlib  
- scikit-learn (KMeans, PCA, StandardScaler)  

---

## 🔍 Key Steps

1. **Data Preprocessing**
   - Handled categorical encoding (Gender)
   - Applied feature scaling using `StandardScaler`

2. **Clustering with KMeans**
   - Determined optimal number of clusters using Elbow Method
   - Applied `KMeans` clustering to assign customers into segments

3. **Dimensionality Reduction**
   - Used `PCA` to reduce features to 2 components for easy visualization
   - Retained ~98% variance in 2D plot

4. **Visualization & Analysis**
   - Created scatter plots to visualize clusters
   - Interpreted each segment's characteristics

---

## 📈 Sample Output

![Cluster Plot](visuals/kmeans_cluster_plot.png)

---

## 📊 Business Use Cases

- Personalized marketing strategies  
- Designing age-specific loyalty programs  
- Improving customer retention by understanding segment behavior  
- Optimizing advertising spend

---

## 📌 Results

- Clustered 200+ customers into 4 meaningful segments  
- Identified patterns across age, income, and spending score  
- Delivered actionable insights for business decisions
