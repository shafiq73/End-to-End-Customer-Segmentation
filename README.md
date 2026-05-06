# Customer Intelligence: Segmentation using K-Means & PCA

## 🚀 Project Overview
This project implements an advanced **Customer Segmentation** pipeline using Unsupervised Machine Learning. The goal is to transform raw retail data into actionable customer personas by analyzing purchasing behavior, demographics, and engagement history.

By leveraging **K-Means Clustering** and **Principal Component Analysis (PCA)**, this model identifies distinct segments to help businesses tailor their marketing strategies.

## 🛠️ Key Features & Engineering
Unlike standard clustering, this project includes a robust preprocessing and feature engineering phase:
- **Total Spending:** Aggregated expenditure across all product categories (Wines, Meat, Gold, etc.).
- **Customer Tenure:** Derived from enrollment dates to track loyalty duration.
- **Family Metrics:** Unified household data to calculate total children.
- **Robust Cleaning:** Automated removal of outliers in Age and Income for higher model accuracy.

## 💻 Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
- **Algorithms:** K-Means Clustering, PCA (Dimensionality Reduction)
- **Metrics:** Silhouette Score, Elbow Method (Inertia)

## 📊 Workflow
1. **Data Cleaning:** Handling missing values and fixing date formats.
2. **Feature Engineering:** Creating high-impact metrics (Age, Total Purchases, etc.).
3. **Scaling:** Normalizing data using `StandardScaler`.
4. **Optimization:** Determining optimal clusters (k=4) via Elbow Plot.
5. **Dimensionality Reduction:** Using PCA to visualize 7D data in a 2D space.
6. **Profiling:** Generating a **Heatmap** to interpret cluster characteristics.

## 📈 Results
The model successfully identifies four unique customer segments, ranging from "High-Value Loyalists" to "Occasional Deal-Seekers," validated with a Silhouette Score to ensure cluster cohesion.

---
*Developed for Professional Portfolio | Data Science & Machine Learning*
