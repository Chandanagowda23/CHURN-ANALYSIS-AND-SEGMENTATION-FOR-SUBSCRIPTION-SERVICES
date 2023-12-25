# Churn Analysis and Segmentation for Subscription Services

## Introduction
Churn analysis is a critical aspect of the e-commerce industry, focused on retaining consumers for long-term economic performance. This project explores the motives behind understanding and mitigating churn, emphasizing the importance of customer segmentation for targeted retention measures.

## Methods Employed
The research, conducted using R, employs four clustering models: k-means, hierarchical clustering, Gaussian Mixture Model (GMM), and Latent Profile Analysis. The chosen hierarchical clustering model with three clusters balances granularity and interpretability. The structured process includes data preparation, PCA, grouping, and cluster characteristics analysis.

## Highlights of the Results
The study reveals three unique client groupings with distinct behavioral tendencies, offering a detailed picture of the client base for targeted actions to address possible churn.

- Cluster 3: Higher values for account age, monthly charges, total charges, and user rating, indicating potentially more established and higher-value users.
- Cluster 3: Higher values for support tickets per month and subtitles enabled, suggesting higher engagement or potential issues.
- Cluster 3: Slightly higher preference for using a mailed check as a payment method compared to other clusters.

## Tailored Churn Mitigation Strategies for Cluster 3
- Utilize age-related metrics to identify potentially more established and higher-value users.
- Tailor retention strategies, such as loyalty programs or exclusive offers, for Cluster 3.
- Implement enhanced customer support initiatives and personalized communications to address unique needs and concerns.

## Conclusion
The use of cluster analysis allows for the discovery of consumer categories, each with its own interests and habits. Analyzing churn patterns within these clusters enables customized retention measures, helping organizations make data-driven choices to minimize churn and increase customer lifetime value.

## Dataset
The dataset used for this project is available on Kaggle: [Predictive Analytics for Customer Churn Dataset](https://www.kaggle.com/datasets/safrin03/predictive-analytics-for-customer-churn-dataset)

## R Version

This project was developed using R version 4.2.2 .

## Usage

1. Clone the repository.
2. Open the R script or R Markdown file.
3. Run the code using R or RStudio.

Feel free to explore the code and adapt it to your needs.



