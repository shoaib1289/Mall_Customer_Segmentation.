# Mall_Customer_Segmentation.
# 📊 Mall Customer Segmentation - Jupyter Notebook

## 📌 Overview
This repository contains a Jupyter Notebook that performs **Mall Customer Segmentation** using clustering techniques like **K-Means clustering**. The goal is to segment customers based on their **age, income, and spending behavior** to help businesses improve marketing strategies.

---

## 📂 Files in This Repository
- **`mall_customer_segmentation.ipynb`** → Main Jupyter Notebook for analysis.
- **`data/mall_customers.csv`** → Dataset used in the notebook.
- **`README.md`** → Documentation file.

---

## 🏗️ Features of the Notebook
✅ **Data Preprocessing** – Loading, cleaning, and exploring the dataset.  
✅ **Exploratory Data Analysis (EDA)** – Visualizing customer trends and relationships.  
✅ **Clustering with K-Means** – Finding customer groups based on spending behavior.  
✅ **Optimal Cluster Selection** – Using the **Elbow Method** to determine the best number of clusters.  
✅ **Data Visualization** – Using **Matplotlib & Seaborn** for insightful graphs.  


## Results

### Data Distribution
- The dataset contains a mix of **age, annual income, and spending score**.
- **Age Distribution:** Shows a varied spread with peaks around the 30-40 age range.
- **Income Distribution:** A skewed distribution with most individuals earning between 40k-80k.
- **Spending Score Distribution:** Bimodal, with peaks at both lower and higher spending scores.

### Gender Insights
- More **female customers** than males.
- Income distribution is **similar across genders**, but **spending scores vary**, with some females having higher spending scores.

### Relationship Insights
- **Income vs Spending Score:** Distinct clusters indicate potential customer segmentation.
- **Age vs Income vs Spending Score:** Certain age groups have higher spending scores.

### Clustering Results
- **Elbow Method:** Suggested **5 clusters** as the optimal number.
- **Customer Segmentation:**
  - **Cluster 0:** High income, low spending score.
  - **Cluster 1:** Low income, high spending score.
  - **Cluster 2:** Moderate income, moderate spending score.
  - **Cluster 3:** High income, high spending score.
  - **Cluster 4:** Low income, low spending score.

- The largest group belongs to **Cluster 0**, while the smallest segment is **Cluster 2**.

### Key Takeaways
- There are clear customer groups based on spending behavior and income.
- High-income individuals tend to have **either very high or very low spending scores**.
- Low-income individuals show **varied spending behaviors**, with some spending high despite low income.


---

## 🔧 Installation & Setup
### **1️⃣ Install Dependencies**
Make sure you have Python installed, then install required libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook
