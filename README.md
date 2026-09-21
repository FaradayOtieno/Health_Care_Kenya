# Geospatial Clustering of Health Facilities in Kenya Based on Location and Ownership Type

This project applies **unsupervised machine learning** to explore patterns in healthcare facility distribution and ownership across Kenya.

The analysis uses **KMeans clustering and Principal Component Analysis (PCA)** to identify groups of health facilities with similar characteristics and examine how ownership and facility attributes vary across the resulting clusters.

## Research Focus

The project explores the following questions:

* What patterns exist in the distribution and ownership of health facilities?
* How do facility characteristics differ across identified clusters?
* Can dimensionality reduction help visualize the structure of the facility data?

## Dataset

The analysis uses data from the **Health Facility Master List (Kenya)**.

Relevant variables include characteristics such as:

* Ownership type
* Facility type
* Services
* Regional or location information, where available

## Methodology

The analysis follows an unsupervised learning workflow:

1. Data preparation and selection of relevant variables
2. Encoding of categorical variables
3. KMeans clustering
4. Principal Component Analysis (PCA)
5. Cluster visualization
6. Group-wise summaries and interpretation

### Techniques Used

* Label encoding for categorical variables
* KMeans clustering
* PCA for dimensionality reduction
* Heatmaps
* Group-wise summaries
* Cluster interpretation

## Cluster Analysis

The analysis identified **four clusters** based on the selected facility characteristics.

The resulting clusters showed differences in ownership and facility characteristics, including patterns involving:

* Government-owned facilities
* Private facilities and practices
* Community and NGO-related facilities
* Specialized private facilities

Cluster labels represent groups identified by the algorithm and should be interpreted in the context of the variables included in the analysis.

## Visualizations

The project includes visual analysis of:

* Ownership distribution by cluster
* PCA representation of the clusters
* Heatmaps showing patterns across groups
* Group-wise comparisons of facility characteristics

## Repository Structure

```text id="9v4v5f"
Health_Care_Kenya/
│
├── data/        # Dataset files
├── results/     # Analytical results and outputs
├── scripts/     # Analysis scripts
├── README.md
├── LICENSE
└── .gitignore
```

## Technologies

* Python
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn

## Purpose

This project demonstrates the application of **unsupervised learning and statistical data analysis to healthcare infrastructure data**.

It forms part of my broader interest in applying data science, machine learning, and quantitative methods to real-world health and development questions.

## License

MIT License

## Author

**Michael Faraday Otieno**

Statistician | Data Science | Machine Learning | AI | Independent Researcher
