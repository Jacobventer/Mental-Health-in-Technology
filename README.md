## Unsupervised Machine Learning Project
Mental Health in Tech 

This project explores mental health survey data from the tech industry using unsupervised machine learning techniques.
It simulates a real-world case where a fictional HR department requests insight into employee mental health patterns to guide targeted wellness initiatives.

Project Objective:
To identify clusters of employees with similar mental health profiles using:
- Data cleaning and feature engineering
- Dimensionality reduction (PCA, t-SNE)
- K-means clustering
- Visualization and interpretation of clusters

Dataset:
- Source: [Kaggle 2016 Mental Health in Tech Survey](https://www.kaggle.com/osmi/mental-health-in-tech-survey)
- 1,433 survey responses with mental health-related questions and demographic data

Techniques Used
- Data cleaning and transformation
- One-hot encoding, binning, standardization
- Dimensionality Reduction: PCA & t-SNE
- Clustering: Elbow method and KMeans
- Visualizations: Cluster plots, summaries, t-SNE mappings

Key Insights
- Identified 3 distinct employee clusters:
  1. **Silent Sufferers** – High disorder rate, low openness
  2. **Resilient Group** – Low disorder rate, stable
  3. **Risky Remote Workers** – Moderate disorder, low supervisor openness, mostly remote

- Provided HR with actionable insights such as:
  - One-on-one counseling for Cluster 0
  - Peer mentorship from Cluster 1
  - Remote wellness check-ins for Cluster 2
 
View the Analysis:
- Jupyter Notebook: [Final_Code.ipynb](https://github.com/Jacobventer/Mental-Health-in-Technology/blob/main/Final%20Code.ipynb)



*Sample Visualization:*

t-SNE Visualization of Menatl Health Survey:
It highlights natural clusters in the dataset, showing how participants group based on their mental health responses. t-SNE is especially useful for uncovering nonlinear patterns that are not easily detected by linear methods like PCA.
![t-SNE Visualization of mental health survey)](https://github.com/Jacobventer/Mental-Health-in-Technology/blob/main/Figures/t-SNE%20Visualization%20of%20Mental%20Health%20Survey%20Responses.png)


PCA Mental Health Status
The PCA projection shows some overlap in mental health status classes, but gives a good overview of data structure.
![PCA Mental Health Status](https://github.com/Jacobventer/Mental-Health-in-Technology/blob/main/Figures/PCA%20Mental%20HEalth%20Status.png)


Work Position Categories:
This distribution shows how job titles were grouped into categories for clearer analysis.
![Work Position Categories](https://github.com/Jacobventer/Mental-Health-in-Technology/blob/main/Figures/Work%20Position%20Categories%20Distribution.png)

Author:
**Jaco Venter**  
Data Science student  
LinkedIn Profile: www.linkedin.com/in/jaco-venter-45502a162


