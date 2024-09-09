Analysis of data of customers of the mall.

Submitted by: Saheel Ahemad (1RF21CS086)

Contents of the CD:
1. readme.txt
2. project.ipynb
3. DSVReport.pdf
4. images

This project presents a comprehensive evaluation and implementation of the K-means clustering algorithm for analyzing mall customer behavior and segmentation. Building upon initial findings from customer data, we aim to identify distinct customer groups based on their shopping patterns and demographics.

Data collection and pre processing:

For our mall customer analysis project using the K-means algorithm, we begin with dataset collection and pre-processing. Our dataset includes features such as CustomerID, Gender, Age, AnnualIncome, and SpendingScore. The pre-processing phase involves cleaning the data by handling missing values and removing duplicates, transforming categorical data like Gender into numerical format, and normalizing numerical features to ensure they're on the same scale. We then conduct exploratory data analysis to understand the distribution and relationships between features, creating visualizations and summary statistics. Finally, we prepare the data specifically for K-means clustering by ensuring all features are numerical and appropriately scaled, and removing the CustomerID from the clustering process as it's merely an identifier. This thorough preparation sets the stage for effective application of the K-means algorithm to derive meaningful customer segments.

Exploratory Data Analysis (EDA):

In our mall customer analysis project, the K-means algorithm is used for exploratory data analysis and segmentation. After scaling the data, we applied K-means clustering and evaluated various metrics to determine the optimal number of clusters, examining values for 2 to 10 clusters. We calculated the Within-Cluster Sum of Squares (WCSS), which typically decreases as the number of clusters increases, to assess cluster compactness. The silhouette score, ranging from -1 to 1 with higher values indicating better-defined clusters, was used to measure cluster cohesion and separation. We also implemented the Calinski-Harabasz score, where higher values suggest better-defined clusters, to evaluate the ratio of between-cluster to within-cluster dispersion. These diverse metrics, each with their own scale and interpretation, provided a comprehensive understanding of cluster quality across different segment numbers. By analysing the trends and optimal points in these metrics, we were able to make an informed decision on the most appropriate number of customer segments, balancing model complexity with explanatory power to ensure our final clustering solution was both statistically sound and practically meaningful for understanding mall customer behavior.

Data Visualization:

Data visualization is a crucial tool for analysing and presenting complex information in an accessible format. This project utilizes various graph types to explore customer segmentation patterns and relationships between key attributes.

The main types of graphs used in this analysis include:
1. Box plots: Show distribution and outliers of numerical data across categories.
2. Scatter plots: Display relationships between two continuous variables.
3. Line charts: Illustrate trends over a continuous interval or time period.
4. Radar charts: Compare multiple quantitative variables.
5. Pie charts: Represent proportions of a whole.
6. Violin plots: Combine box plots with kernel density estimates to show probability distribution.
7. K-means clustering visualizations: Illustrate groupings based on similar characteristics.
8. Multi line charts: Illustrate the comparison of the different evaluation metrics.
These diverse visualization techniques provide comprehensive insights into customer behavior and segmentation.