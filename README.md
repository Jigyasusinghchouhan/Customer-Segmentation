# Customer Segmentation Using K-Means Clustering

This project demonstrates how to perform customer segmentation using the K-Means clustering algorithm. Customer segmentation allows a company to customize its relationships with customers based on their behavior and needs. In this case study, we will focus on the behavioral aspect of customer segmentation using an actual sales dataset from an e-commerce company.

## Business Case

The business case revolves around the question: Can the customer base be grouped to develop customized relationships? We will approach this question from a behavioral perspective, considering features such as the number of products ordered, average return rate, and total spending.

## Data Preparation 

The dataset contains approximately 25,000 unique customers with their order information. We will calculate three key features for each customer: 
- Number of products ordered
- Average return rate
- Total spending

These features will be used for visualization and algorithm explainability.

## Segmentation with K-Means Clustering

We will use the K-Means clustering algorithm to segment the customer base. K-Means works by initializing centroids, assigning data points to the closest centroid, and moving centroids to the average of the points in the cluster. This process is repeated until convergence.

Hyperparameter Tuning:
- Selecting the appropriate number of clusters (k) is crucial. We will use the elbow method to determine the optimal value for k.

## Visualization and Interpretation of the Results

With the optimal number of clusters, we will visualize how customer groups are created using K-Means. Each group will be interpreted based on their characteristics, such as spending habits and return rates.

- Blue: Customers with low spending, newcomers.
- Red and Purple: Customers who know the brand and order multiple products.
- Green: Highly favorable customers with high spending and low return rates.

The overall strategy is to preserve the most favorable customer group (green), improve the behavior of the blue group, and maintain engagement with the red and purple groups.

## Conclusion

This project demonstrates the use of unsupervised machine learning for customer segmentation. By understanding customer behavior, companies can tailor their strategies and relationships to maximize revenue and customer satisfaction.

About the interview:
The interview process for this case study was practical and realistic, allowing candidates to showcase their data science skills. Practical data science interviews like this benefit both candidates and employers.

For the full article and code, please refer to the [GitHub repository](link-to-your-github-repo).
