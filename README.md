# Global CO2 Emissions & Economic Clustering Project

This project analyzes global data on population, GDP, cement-related CO2 emissions, and total CO2 emissions. Using KMeans clustering, countries are grouped based on similar economic and environmental profiles. The goal is to identify patterns and clusters that can inform policy and sustainability decisions.

---

## Project Structure

- dataset.csv — Raw input data
- BIGdfinal project.ipynb — Main Jupyter notebook with all code and results
- Global_cleaned.csv — Cleaned dataset (output)
- clustered_data.csv — Clustered data for Power BI (output)
- README.md — This file

---

## How to Run

1. Clone this repository.
2. Place your dataset.csv in the root directory.
3. Open BIGdfinal project.ipynb in Jupyter or VS Code.
4. Run the notebook step by step.

---

##  Workflow Overview

### 1. Data Preparation

- Load the dataset.
- Display column names.
- Clean missing values.
- Encode categorical columns.
- Scale numerical columns.

### 2. Exploratory Data Analysis

- Show descriptive statistics.
- Visualize distributions (histograms, pairplots).
- Correlation heatmap.

### 3. Clustering

- Select features: population, gdp, cement_co2, co2.
- Scale features using MinMaxScaler.
- Use KMeans for clustering.
- Assign cluster labels.
- Evaluate clustering with silhouette score.
- Save clustered data for Power BI.

### 4. Cluster Summary Table

- Group by cluster and calculate mean values for each feature.
- Export summary for dashboard use.

### 5. Visualization

- Scatter plot of GDP vs CO2 colored by cluster.
- Power BI dashboard (see below).

---

## 💡 Innovation

- Automated selection of optimal cluster number using silhouette score.
- Modular functions for feature selection, scaling, clustering, and evaluation.

---

## 📊 Power BI Dashboard

*Visuals:*
- Cluster distribution map
- Cluster summary table (average values per cluster)
- GDP vs CO2 scatter plot (colored by cluster)
- Cluster size pie chart
- Silhouette score card
- Insights & narrative text boxes

*How to use:*
1. Import clustered_data.csv and cluster_summary.csv into Power BI.
2. Add visuals as described above.
3. Use slicers for region or cluster if desired.

---

## License

MIT License

---

**Feel free to fork, adapt, and use this workflow for your own clustering
here are some screenshots of the procedures
![images](image_path_or_url)
