# 🌍 Country Clustering Analysis using K-Means

### 🧠 AI Integrated Data Science Project by Abhiram  
An **Unsupervised Machine Learning** project that groups countries based on their **socioeconomic and health indicators** using **K-Means Clustering** and **PCA visualization**.

---

## 📘 Overview

This project performs **country-level clustering** to identify global development patterns.  
By analyzing key indicators such as GDP, Life Expectancy, Health, and Fertility, we reveal distinct clusters representing:

- Developed Nations 🌟  
- Developing Nations 🌱  
- Emerging Economies 🚀  

The project demonstrates data preprocessing, clustering, visualization, and insight generation using Python.

---

## 🧩 Project Goals

- Clean and preprocess socioeconomic country data  
- Apply **K-Means** clustering to group countries with similar characteristics  
- Use **PCA (Principal Component Analysis)** for dimensionality reduction and 2D visualization  
- Summarize and interpret the key features of each cluster  

---

## 🧰 Technologies & Libraries Used

| Category | Libraries |
|-----------|------------|
| Data Handling | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn` |
| Machine Learning | `scikit-learn` |
| Notebook Environment | `Jupyter Notebook` |

---

## 📊 Dataset Information

The dataset includes features such as:

- **Exports (%)**
- **Imports (%)**
- **Health expenditure (% of GDP)**
- **Income per person**
- **Inflation (%)**
- **Child Mortality Rate**
- **Life Expectancy (years)**
- **Total Fertility Rate**
- **GDP per Capita ($)**

Each row represents a country, and each column represents an economic or health metric.

---

## 🤖 Model: K-Means Clustering

- Number of Clusters (K): **3**
- Algorithm: **K-Means**
- Distance Metric: **Euclidean**
- Dimensionality Reduction: **PCA (2 Components)**

---

## 📈 Visualizations

### 1️⃣ Cluster Size Distribution  
Displays the number of countries in each cluster:

![Cluster Sizes](d861f990-36e3-4dc1-9cfc-d6860b15a70a.png)

### 2️⃣ PCA 2D Projection  
Visualizes how countries are grouped in a 2D space:

![Country Clusters PCA](54e88fe3-64f3-42c1-aed3-fcafec155cd2.png)

---

## 🧮 Cluster Summary

| Cluster | Exports | Health | Imports | Income | Inflation | Child Mortality | Life Expectancy | Fertility | GDP per Capita |
|----------|----------|---------|----------|----------|------------|-----------------|-----------------|------------|----------------|
| 0 | 176.00 | 6.79 | 156.67 | 64033.33 | 2.47 | 4.13 | 81.43 | 1.38 | 57566.67 |
| 1 | 29.51 | 6.14 | 43.63 | 4142.13 | 11.23 | 76.49 | 61.82 | 4.44 | 1944.54 |
| 2 | 44.95 | 7.28 | 45.75 | 24675.67 | 5.56 | 12.92 | 76.25 | 1.97 | 19196.19 |

---

## 🔍 Interpretation

- **Cluster 0 – Developed Nations**  
  High income, strong health systems, low mortality, and low fertility.

- **Cluster 1 – Developing Nations**  
  Low GDP, high fertility, high mortality, and low life expectancy.

- **Cluster 2 – Emerging Economies**  
  Moderate income, improving life expectancy, balanced fertility and growth.

---

## 🚀 Future Enhancements

- Integrate **live World Bank / IMF API** data  
- Compare results using **DBSCAN** or **Hierarchical Clustering**  
- Build an **interactive dashboard** using **Streamlit** or **Power BI**  
- Perform **time-series analysis** of development trends  

---

