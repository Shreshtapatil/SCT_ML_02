# 📊 SCT_ML_02  
### Internship Task 02 – Customer Segmentation using K-Means Clustering  
💼 SkillCraft Technology | 📅 July 2025

---

## 🧠 Project Overview
This project is part of my internship at **SkillCraft Technology**, under **Task ID: SCT_ML_02**.  
It aims to segment mall customers into distinct groups based on **Annual Income** and **Spending Score**, using the **K-Means Clustering algorithm**. This helps in understanding customer behavior for better marketing strategies.

---

## 🗂 Dataset
The dataset used is `Mall_Customers.csv`, consisting of:
- `CustomerID`: Unique identifier
- `Genre`: Gender
- `Age`: Age of customer
- `Annual Income (k$)`: Income in thousands
- `Spending Score (1-100)`: Score based on customer behavior

---

## 📚 Libraries Used
- `pandas` – Data manipulation  
- `numpy` – Numerical operations  
- `matplotlib` – Plotting graphs  
- `seaborn` – Data visualization  
- `scikit-learn` – Machine learning (clustering, scaling)

---

## ⚙️ Methodology
- Selected features: `Annual Income (k$)` and `Spending Score (1-100)`
- Scaled data using `StandardScaler`
- Determined optimal clusters using **Elbow Method**
- Applied **KMeans clustering** with 5 clusters
- Visualized customer segments

---

## 📈 Visualizations

### 📌 Elbow Method  
Used to determine the optimal number of clusters:  
![elbow_plot png - Copy](https://github.com/user-attachments/assets/a9733b32-92d3-4c38-9ed8-2ed482c8fe34)


### 📌 Customer Segmentation  
Final clusters based on income and spending behavior:  
![cluster_plot png](https://github.com/user-attachments/assets/25597601-3cae-4d99-a0ac-b01ec06bd62a)


---

## ✅ Results Summary
- Successfully segmented customers into **5 clusters**
- Clear differentiation between high/low income and spending groups
- Results saved to `clustered_customers.csv`
- Visual insights support strategic marketing segmentation

---

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SCT_ML_02-Customer-Segmentation.git
