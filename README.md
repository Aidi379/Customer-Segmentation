# Customer-Segmentation
Background：

The customer company is a small to medium-sized online retail business with approximately 80 employees. Established in 1981, it primarily sells daily necessities. Two years ago, the company transitioned to an online model, launching its own website and leveraging Amazon.co.uk for additional sales. This shift has resulted in a steady and healthy customer base across the United Kingdom and Europe, and the company has accumulated extensive data on its customers.

Business Challenge：

The company has transactional data from customers who ordered from their websites or canceled their orders. It aims to develop customer-centric business intelligence and create more customized marketing strategies. The goal is to better understand customer behaviors and preferences, thereby enhancing the effectiveness of customer-centric marketing and increasing sales.

Solution：

To address the business challenge, the following steps were undertaken:

•	Data Cleaning: This involved handling missing values, duplicates, incorrect data, and data errors.

•	Feature Engineering: Creating a new dataset based on customer shopping behaviors, including metrics such as:

a.	RFM (Recency, Frequency, Monetary) analysis to get days since last purchase, total transactions, total products purchased, total spend, and average transaction value.

b.	Product diversity analysis to get unique products purchased.

c.	Shopping behavior analysis to get average days between purchases, favorite shopping day and hour, and geographic features.

d.	Cancellation patterns analysis to get cancellation frequency and rate.

e.	Spending trends analysis to get monthly spending mean, spending variability, and overall spending trend.

•	Data Preprocessing: Undertake feature scaling and dimensionality reduction to streamline the data, enhancing the efficiency of the clustering process.

•	Customer Segmentation using K-Means Clustering: Segment customers into distinct groups using K-means, facilitating targeted marketing and personalized strategies.

•	Cluster Analysis: Analyze and profile each cluster to develop targeted marketing strategies 


Findings and Recommendations：

We found out some useful patterns for each group of customers and gave out some recommendations based on their shopping behaviors.

Casual Weekend Shoppers

Characteristics:

•	Shop less frequently and spend less money.
•	Fewer transactions and fewer products purchased.
•	Prefer shopping on weekends.
•	Stable, low spending habits with minimal monthly fluctuations.
•	Rarely cancel transactions.
•	Lower average transaction value.

Recommendations:
•	Target these customers with promotions and recommendations on weekends.
•	Focus on engagement strategies to increase their shopping frequency.

Occasional Big Spenders:

Characteristics:

•	Infrequent shoppers but spend a significant amount when they do shop.
•	High spending trend, with increasing spend over time.
•	Prefer shopping late in the day, mostly residing in the UK.
•	Moderate number of cancellations, likely due to higher spending.
•	High average transaction value, indicating a preference for premium products.

Recommendations:

•	Tailor marketing messages to busy professionals who prefer shopping in the evenings.
•	Highlight premium products and offer exclusive deals to encourage more frequent purchases.

Eager Early-Bird Shoppers:

Characteristics:

•	High total spend and purchase a wide variety of unique products.
•	Frequent transactions with a high cancellation frequency and rate.
•	Low average time between purchases, shopping early in the day.
•	High variability in monthly spending.
•	Decreasing spending trend despite high overall spend.

Recommendations:

•	Offer early bird specials and morning promotions to align with their shopping habits.
•	Implement a loyalty program to encourage consistent spending and reduce cancellations.
•	Provide personalized recommendations and limited time offers to stimulate purchases and stabilize spending patterns.

By leveraging these insights and implementing targeted marketing strategies, the company can enhance customer engagement, optimize marketing efforts, and drive increased sales across different customer segments.
