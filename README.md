# Myntra-Online-Retail-Customer-Segmentation

In today’s competitive retail landscape, understanding customer behavior is crucial for personalized marketing and long-term loyalty. This project focuses on customer and product segmentation for Myntra Gifts Ltd., the UK-based division of Myntra, using unsupervised machine learning techniques on real-world transactional data.

The dataset spans two years (Dec 2009–Dec 2011) and includes detailed records of online orders, capturing information such as invoice numbers, product descriptions, quantities, unit prices, customer IDs, and countries. The goal is to uncover purchasing patterns, customer segments, and product performance to inform business decisions in marketing, inventory, and pricing.

**The project follows a structured pipeline:**

Data Understanding and Cleaning: The dataset is explored for structure, missing values, and outliers. Canceled orders and invalid entries are removed, and features such as TotalSales are derived for analysis.

Exploratory Data Analysis (EDA): Temporal trends, top-selling products, and country-level sales distribution are visualized. Customer buying behavior is assessed to understand high-value segments and seasonal demand.

Feature Engineering and Scaling: Features such as purchase month, total sales per invoice, and customer frequency are engineered. Scaling is applied for clustering purposes.

**Clustering Models:**

K-Means Clustering: The Elbow Method and Silhouette Score help determine the ideal number of clusters, grouping customers based on their purchasing behavior.

Hierarchical Clustering: Dendrograms are used to validate customer segmentation and explore relationships between clusters.

Evaluation and Interpretation: Clusters are analyzed to profile customer types—such as bulk buyers, seasonal shoppers, or loyal frequent purchasers. These profiles offer valuable insight into customer needs and behaviors.

**Business Impact:**

This segmentation enables tailored promotions, improved inventory planning, and targeted communication strategies. For instance, high-revenue customers can be prioritized for loyalty programs, while low-frequency buyers can be re-engaged through personalized offers.

**Future Work:**

The project can be extended by integrating RFM analysis, building predictive models for customer lifetime value, or deploying insights via dashboards for real-time business decision-making.

This project showcases the power of data-driven strategies in e-commerce and highlights how machine learning can enhance customer relationship management, product planning, and revenue optimization.
