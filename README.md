# Geospatial Clustering of Health Facilities in Kenya Based on Location and Ownership Type

This project uses unsupervised machine learning to analyze health facilities in Kenya based on their **ownership** and ** regional patterns in healthcare facility distribution**. 
The goal is to uncover patterns that can inform health planning, investment, or policy.

## 🗂️ Dataset
- Health Facility Master List (Kenya)
- Includes variables like:
  - Ownership (public, private, NGO, religious)
  - Facility type and services
  - Region (optional)

## 🧠 Techniques Used
- Label Encoding for categorical fields
- KMeans clustering (4 clusters)
- PCA for dimensionality reduction and visualization
- Heatmaps and group-wise summaries for interpretation

## 📊 Key Insights
- Cluster 0: Predominantly government-owned facilities
- Cluster 1: Dominated by private practice (clinics, specialists)
- Cluster 2: Mixed community/NGO ownership
- Cluster 3: Specialized private practices

## 🖼️ Visuals
- Ownership distribution by cluster
- PCA scatter plot of clusters
- Heatmaps showing ownership dominance

## 🛠️ Tools
- Python (pandas, scikit-learn, matplotlib, seaborn)

## 📌 Conclusion
This project highlights how clustering can expose hidden structure in healthcare infrastructure. The results may guide resource allocation, policy targeting, or further analysis in health systems research.

## 📄 License
MIT License
