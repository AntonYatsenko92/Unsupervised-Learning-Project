# machine_learning_project-supervised-learning

## Problem Statement

The purpose of this project to assess data the Wholesale Data and cluster the data in various groups to better explain the patterns of customers and regions based on their annual spending habits

## Approach

The project approach focuses on four (4) key steps:

1. Exploratory Data Analysis - in this step the aim is to explore and understand what variables are available for their analysis and whether the data requires and cleaning or modification
2. Clean & Prepare Data - in this step data is cleaned to remove any outliers based on the EDA process and then standardized and balanced accordingly to ensure results are consistent and reliable
3. Execute Unsupervised Learning Models - three (3) models were conducted in total: K-Means, Hierarchical Clustering, and Principle Component Analysis (PCA)

## Results

The result of each model were subject to interpretation but the following inferences were made:

K-Means - the optimal number of clusters was determined to be four (4) based on plotting the data and conducting the "elbow method" analysis
Hierarchical Clustering - the optimal number of clusters was determined to be three (3) based on he height of the Dendrograms
PCA - the optimal number of clusters was determined to be four (4) based on the explained variance ratio, which illustrated that 90% of the variance was explained by four components

## Conclusion

Based on the model conducted and the analysis done these are my findings:

1) Small datasets such as this one are tough to work with. I initially chose to look at outliers outside of the IQR, however, this removed too much data and settled on a very thin range. Ideally, if we had more data this would be better in predicting the outcomes
2) KMeans clustering is a useful tool only if iterated through a number of different features as randomly guessing the clusters is often challenging. In this case it was quite easy as we knew that the categories could fall into 1/6 groups, however, in many real world datasets this is not the case
3) Hierarchical clustering is useful for visualizing the dataset and identifying the number of clusters since our overall dataset was quite small, however, I can see this becoming impractical very quicky as the dataset grows
4) PCA is the most useful of all the Unsupervised Learning algorithms as it provides explainability of all of the components in a clear and easy way to understand. Furthermore, as algorithms continue to get more complex, easily being to identify which core features can explain the majority of the variability is a very useful feature
