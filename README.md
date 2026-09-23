# Unsupervised-Learning-Clustering
# Airline Customer Value Analysis

**Dataset** : [source](https://github.com/aliffiaaps-coder/Unsupervised-Learning-Clustering/blob/main/flight_train.csv) <br>
**Notebook** : [view](https://github.com/aliffiaaps-coder/Unsupervised-Learning-Clustering/blob/main/study_case_clustering.ipynb)<br>

<br>

**Table of Contents**
- [Business Understanding]( )
- [Workflow]()
- [Insight]()
- [Modeling and Evaluation]()
<br>


## 📂 Business Understanding
### Problem Statement
An airline has customer data covering a highly diverse range of market segments, from business travelers who prioritize comfort to price-sensitive tourists. The current challenge is understanding the diversity of behaviors and specific needs of each customer segment. The marketing approach currently is generic, resulting in all customers receiving the same communication strategies and promotional offers. Consequently, this strategy makes marketing messages less relevant to most customers and fails to effectively build long-term loyalty.
The lack of measurable segmentation based on flight patterns, spending levels, and discount sensitivity leads to inefficient allocation of the company’s promotional budget. This risks offering excessive discounts to high-spend customers who are actually not price-sensitive, thereby eroding profit margins. Therefore, it is necessary to segment customers into several groups based on behavioral data and profitability, and then design personalized targeted marketing strategies for each group.
### Goals
Identify airline customer segments based on behavioral patterns and profitability in order to design precise targeted marketing strategies, thereby improving the efficiency of promotional budget allocation and maximizing Customer Lifetime Value (CLV).

### Objectives
Categorize customers into distinct groups based on flight patterns, spending levels, and discount sensitivity.
Provide recommendations for targeted marketing programs tailored to the profitability of each customer segment.



## 🔁Workflow  
EDA : Verify data for any missing values, duplicate values, and anomalies, and sort out the same.
Pre-processing : Make sure data is consistent and clean with respect to data type, data format, and values used.
Analysis: Conducting statistical tests to ensure data integrity and prevent issues with multicollinearity.
Modeling: Determining customer segmentation using K-Means and Agglomerative Clustering Models, then selecting the algorithm based on evaluation.
Deployment: Creating visualizations and calculating Silhouette Scores based on the Clustering Model evaluation.
<br>

## 🔍Exploring the content of variables
The customer segmentation model used in this business is LRFMC (*Length, Recency, Frequency, Monetary, Discount*), with the following selected features:
- **L (Length / Relationship): ** Determines how loyal a customer is as an airline member.
- **R (Recency):** Determines when the customer last used the company’s flight services.
- **F (Frequency):** Indicates the customer’s level of activity.
- **M (Monetary):** Total distance traveled is directly proportional to the amount of money customers spend.<br>
- **C (Discount):** Determines the customer’s price sensitivity.

<br>

## 📂 Modeling and Evaluation
- Optimal number of clusters: k = 3
- The experiment used the K-Means and Agglomerative algorithms
- The K-Means clustering model performed best, with a high Silhouette Score (0.27)
- K-Means was able to cluster the airline’s LRFMC customer data
<br>

## 🕵🏻‍♂️Business Insight 
Based on the LRFMC analysis, the airline’s customers were grouped into the following three customer behavior clusters:
- Cluster 0 (Churn Risk): Passive customers at high risk of switching to a competitor airline, for 22.34% of the total data.
- Cluster 1 (Potential Loyal): Moderately active middle-class customers who fly frequently constitute the largest group, for 66.84% of total customers.
- Cluster 2 (VIP): High-end frequent flyers are a minority, for 10.82% of total customers.

## 📌 Business Recommendations
Launch a re-activation campaign (Win-Back Strategy) 
Boost loyalty through gamification (Upselling Strategy)
Implement an exclusive appreciation program for this cluster (Retention Strategy). 




