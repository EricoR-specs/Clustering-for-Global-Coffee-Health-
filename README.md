# Global Coffee Health Dataset: Clustering & Lifestyle Analysis

## 👤 Author  
**Name:** Muhammad Erico Ricardo  

## 📂 Dataset  
[Global Coffee Health Dataset (Kaggle)](https://www.kaggle.com/datasets/uom190346a/global-coffee-health-dataset?resource=download)

---

## 📖 Introduction  

The **Global Coffee Health Dataset** contains **10,000 synthetic records** designed to reflect real-world patterns of **coffee consumption, sleep behavior, and health outcomes** across **20 countries**.  

It includes demographic, lifestyle, and health-related attributes such as:  

- Daily coffee & caffeine intake  
- Sleep duration & quality  
- BMI, heart rate, stress levels  
- Physical activity & occupation  
- Smoking & alcohol consumption  
- Reported health issues  

This dataset was designed to capture **realistic correlations** observed in research—such as caffeine’s impact on sleep, stress, and overall health.  

---

## 🔧 Applications  

This dataset is highly suitable for:  

- **Statistical analysis**  
- **Predictive modeling**  
- **Lifestyle and wellness studies**  
- **Health informatics research**  
- **Benchmarking for clustering & ML methods**  

Example use cases:  

- Exploring correlations between **coffee intake, sleep quality, and health outcomes**  
- Analyzing **lifestyle factors** such as physical activity, smoking, and alcohol consumption  
- Building **predictive models** for sleep quality, stress levels, or potential health risks  
- Comparing **demographic and country-level caffeine consumption** patterns  

---

## 📊 Analysis Summary  

### ✅ Data Preprocessing  
- `Health_Issues` had **59.41% missing values**, imputed with `"None"`.  
- Converted categorical variables (`Gender`, `Country`, `Sleep_Quality`, etc.) into dummy variables.  
- Standardized numerical features with `StandardScaler`.  

### 🔎 Clustering Results  
- Applied **K-Means clustering** with `k=5`.  
- Silhouette Score ≈ **0.092** → low separation between clusters.  
- **PCA 2D visualization** showed significant overlap among clusters.  

### 📌 Key Cluster Insights  
- **Cluster 0:** Moderate age & coffee intake, good sleep, low stress, mostly healthy.  
- **Cluster 1:** Lower sleep duration, higher stress, more health issues.  
- **Cluster 2:** Lowest coffee intake, good sleep, low stress, minimal health issues.  
- **Cluster 3:** Moderate coffee intake, mix of stress & health issues, notable smokers.  
- **Cluster 4:** Low coffee intake, good sleep, low stress, higher alcohol consumption.  

---

## 🚀 Next Steps  

- Try **different numbers of clusters** (e.g., elbow method, silhouette optimization).  
- Explore **alternative clustering algorithms** (DBSCAN, Agglomerative).  
- Perform **feature engineering** for improved cluster separation.  
- Conduct **in-depth profiling** of each cluster for meaningful lifestyle insights.  

---

## 📌 Tech Stack  

- **Python**  
- **Pandas / NumPy** (data preprocessing)  
- **Scikit-learn** (clustering, scaling, PCA)  
- **Matplotlib / Seaborn** (visualizations)  

---

## 📜 License  

This project is for **educational and research purposes** only. Dataset sourced from [Kaggle](https://www.kaggle.com/datasets/uom190346a/global-coffee-health-dataset).  
