# statistical-datamining
# README:  Statistical Learning and Data Analysis

## Overview
This repository highlights solutions and implementations from my graduate coursework in Statistical Learning and Data Analysis. Each section presents key concepts, methodologies, and results from the projects demonstrating the application of statistical and machine learning techniques in various contexts.

---

## Clustering and Principal Component Analysis (PCA)

### Topics Covered
1. **Clustering Analysis**:
   - K-means and hierarchical clustering on the `chorSub` dataset.
   - Optimal cluster determination using elbow plots, silhouette analysis, and dendrogram evaluation.
   - Justification for choosing different values of `k` for clustering methods.

2. **Principal Component Analysis (PCA)**:
   - Analysis on diamond dataset to determine principal components.
   - Identification of variance explained by components.
   - Correlation between the first principal component and diamond price.
   - Visualizing clusters using PCA and evaluating separability.

### Results
- Optimal `k` for K-means clustering was found to be 4 using elbow and silhouette methods.
- Hierarchical clustering suggested `k=5` based on dendrogram height analysis.
- PCA revealed that the first principal component accounted for 65.54% of the variance, and three components were needed to explain over 90%.
- Strong correlation (0.89) observed between the first principal component and price, highlighting its predictive power.

---

## Network Analysis and Link Prediction

### Topics Covered
1. **Network Transformations**:
   - Analyzing the `UKFaculty` network.
   - Converting directed networks to undirected and performing structural analyses.

2. **Link Prediction**:
   - Deletion of 8% edges to create noisy datasets.
   - MCMC for hierarchical random graphs and link recovery based on graph structures.

3. **Visual and Statistical Evaluation**:
   - Visualization of graph structures before and after edge deletion.
   - Statistical evaluation of predicted versus deleted edges.

### Results
- Achieved meaningful link recovery using MCMC, showcasing the predictive capacity of graph-based models.
- Visualizations highlighted the clustering structure of the `UKFaculty` dataset.

---

##  Conditional Independence, PageRank, and Bayesian Networks

### Topics Covered
1. **Graphical Models**:
   - Testing conditional independence relationships in different network structures.

2. **PageRank Analysis**:
   - Computation of PageRank for web graphs under varying damping factors.
   - Sensitivity analysis of damping constants on node importance and ranking.

3. **Bayesian Network Design**:
   - Constructed a Bayesian network satisfying specified independence conditions.

### Results
- Conditional independence tests revealed insights into graph connectivity and dependencies.
- PageRank analysis showed the impact of damping factors on ranking, with central nodes gaining importance at higher damping levels.
- Successfully designed a Bayesian network with dependencies and independencies matching given constraints.

---

## Key Takeaways
- Application of statistical and machine learning techniques to real-world datasets.
- Effective use of clustering, PCA, and network analysis to derive meaningful insights.
- Development of advanced graphical models and link prediction algorithms.

---

## How to Explore
- Open implementation files to explore the detailed code for each assignment.
- Check visualizations and statistical evaluations included in the reports for insights into the results.

This repository serves as a portfolio of my coursework, showcasing my understanding and application of key topics in statistical learning and data analysis.

