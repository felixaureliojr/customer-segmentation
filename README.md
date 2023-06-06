# Customer Segmentation
Customer segmentation is a crucial technique in marketing and business strategy that involves dividing a customer base into distinct groups based on various characteristics. In this project, the elbow method and silhouette score were employed to determine the optimal number of clusters for customer segmentation. The analysis focused on age, annual income, and spending score of male and female customers. The findings revealed that the highest spending score for both genders was observed in the age group of 25-30 years, with significant spending power also seen in the 20-40 age range. High annual income was observed among customers aged 25-45 for both genders. Based on the K-Means clustering algorithm, five clusters were chosen, each representing different customer profiles. Notably, two target customer clusters were identified: one with low annual income but high spending score, and the other with high annual income and high spending score. The analysis suggested that age alone may not be a strong predictor of spending behavior, as no distinct cluster was observed in the age versus spending score analysis. These insights provide valuable information for businesses seeking to tailor their marketing strategies and effectively engage different customer segments.

## About the dataset
The dataset used in this project revolves around the analysis of mall customers, providing valuable insights into their characteristics and spending patterns. The dataset comprises five columns: CustomerID, Gender, Age, Annual Income (k$), and Spending Score (ranging from 1 to 100). The Spending Score is a metric assigned to each customer based on predefined parameters, such as customer behavior and purchasing data. This dataset offers a comprehensive view of the mall's customer base, allowing businesses to gain a deeper understanding of their target audience.

Link to dataset: https://github.com/avirichie/Customer-Segmentation-using-Unsupervised-Learning

The main objectives of this project are the following:
- understand the target customers for the marketing team to plan a strategy
- identify the most important shopping groups based on income, age, and mall shopping score
- identify an ideal number of groups or clusters with a label for each

## Methodology

The methodology used in this project can be summarized as follows:

1. **Exploratory Data Analysis (EDA):**
- Conducted thorough analysis of the mall customers dataset to understand its structure and patterns.
- Examined the distribution and relationships of variables through statistical techniques and visualizations.

2. **Determining Optimum Clusters:**
- Employed the elbow method and silhouette score to identify the optimal number of clusters.
- Utilized the elbow method to locate the point of inflection in the within-cluster sum of squares (WCSS) curve.
- Calculated the silhouette score to assess cluster quality and separation.

3. **K-Means Algorithm for Segmentation:**
- Applied the K-Means algorithm to create distinct customer segments based on features like age, annual income, and spending score.

4. **Summary Statistics on Clusters:**
- Computed summary statistics for each cluster.
- Analyzed the average age, annual income, and spending score of male and female customers within each cluster.

5. **Data Visualization:**
- Employed various visualization techniques such as scatter plots, bar charts, and box plots.
- Visualized the distribution of customers across clusters and illustrated relationships between variables.

This methodology facilitated a comprehensive exploration of the dataset, determination of optimal clusters, segmentation using the K-Means algorithm, analysis of summary statistics, and effective visualization of results. These steps provided valuable insights into the segmentation of mall customers, enabling businesses to tailor their marketing strategies and cater to the specific needs and preferences of different customer segments.

## Results and Evaluations

Based on the results of this project, it can be summarize the findings as follows:

1. The average age, annual income, and spending score for female customers are as follows: Average Age: 38.10, Average Annual Income: 59.25, Average Spending Score: 51.53.For male customers, the average age is 39.81, the average annual income is 62.23, and the average spending score is 48.51.

2. The highest spending score for both genders is observed in the age group of 25-30 years old. It is noteworthy that there is also significant spending power observed in the age group ranging from 20-40 years old.

3. High annual income is observed in the age group of 25-45 years old for both male and female customers.

4. The elbow method and silhouette score method suggest that the optimal number of clusters to be used is either 5 or 6. In this analysis, 5 clusters were chosen as the best option.

5. The clustering algorithm with 5 clusters yielded the following groups:

- Cluster 1: Customers with low annual income and high spending score (Target)
- Cluster 2: Customers with medium annual income and medium spending score
- Cluster 3: Customers with high annual income and low spending score
- Cluster 4: Customers with high annual income and high spending score (Target)
- Cluster 5: Customers with low annual income and low spending score

6. The analysis identified two target customer clusters:
- Cluster 1: Customers with low annual income and high spending score (61% Female & 39% Male)
- Cluster 4: Customers with high annual income and high spending score (54% Female & 46% Male)

7. There was no distinct cluster observed in the age vs. spending score analysis, indicating that age alone may not be a strong predictor of spending behavior.

These findings provide valuable insights into the characteristics of customers and their spending patterns, allowing for a better understanding of the target audience and potential marketing strategies.

## Appendix
Compilation of some graphs generated in this project:
![Customer Segmentation/Segmentation.png](https://github.com/felixaureliojr/customer-segmentation/blob/7d24d7802590da6f7af36baf7286f29bdb82d49c/Customer%20Segmentation/Segmentation.png)
