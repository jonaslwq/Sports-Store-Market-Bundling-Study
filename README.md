# Market Basket Analysis - ReadMe

## Overview
This project focuses on conducting a market basket analysis for Decathlon Singapore's online transactions to introduce bundle deals and increase the average basket size. The analysis aims to identify products that are frequently purchased together and create effective bundling strategies to boost sales volume and turnover. The project involves three main considerations: Recommendation System, Customer Segmentation, and Sales of Underperforming Products. Additionally, A/B testing is proposed to evaluate the effectiveness of bundle deals.

## 3.a. Overview
### 3.a.i. Goal:
The goal of this experiment is to introduce bundle deals to increase the average basket size for online transactions. By offering multiple products at a discounted price, this encourages an increase in sales volume and ultimately higher turnover.

### 3.a.ii. Methodology
The main methodology proposed is to use A/B testing based on the selection of products in the analysis. The selection of products for bundling will be based on three main considerations:

1. **Recommendation System:**
Utilizing historic transaction data, a recommendation system will be implemented to identify products that are often purchased together or have a high affinity, making them suitable candidates for bundling.

2. **Customer Segmentation:**
Customer base will be segmented using various criteria such as demographics, purchase history, and preferences. Understanding different customer segments will help identify unique preferences and behaviors, guiding the selection of the right products for each segment's bundling strategy.

3. **Sales of Underperforming Products:**
Sales performance of individual products will also be considered. Products that are underperforming or have lower sales may benefit from bundling with more popular items, increasing their visibility and sales potential.

By combining these considerations, the aim is to identify the most suitable products for bundling, which will drive sales volume and lead to higher turnover.

## 3.b. Analysis based on considerations
In this segment, the three considerations will be explored in depth to find potential products that would benefit most from bundling deals.

### 3.b.i. Recommendation System
A graph data structure will be implemented to track the number of items that are bought together in the same transaction. This will help identify products with a strong relationship, making them suitable for bundle deals. The analysis will focus on "Sports" and "Product Type" categories, considering broader categories to widen the scope of bundling and provide customers with more choices.

### 3.b.ii. Customer Segmentation
Customer profiling will be conducted to identify the types of customers and products that have higher affiliation. Four main customer segments will be considered: High-Value Customer, Loyal Customer, Churned Customer, and Non-members. Targeted bundle deals and marketing strategies can be employed for each group to encourage multiple product purchases.

### 3.b.iii. Sales of Underperforming Products
Sales data for sports categories and product types will be evaluated to identify underperforming products. Bundle deals with popular products will be considered to boost sales and increase exposure for underperforming items.

## 3.c. A/B Testing
For each bundle deal, A/B testing will be conducted over a 2-week period to evaluate its effectiveness. The success metric will be the average sum of turnover generated over the 2 weeks.

### 3.c.i. Problem Statement
The objective is to test if a bundle deal is well-received by online customers, as measured by the average sum of turnover per day per user.

### 3.c.ii. Hypothesis Testing
Null hypothesis: The average sum of turnover per day per user between having bundle deals and no bundle deals are the same.
Alternative hypothesis: The average sum of turnover per day per user with bundle deals is higher than no bundle deals.

Significance Level: 0.05 (Reject null hypothesis if P-value is less than 5%)

### 3.c.iii. Power Analysis to determine Statistical Power
Power analysis will be performed to determine the statistical power of the experiments. Factors such as sample size and effect size will be considered to ensure sufficient statistical power.

## 3.d. Conclusion and Business Insights
The market basket analysis provides valuable insights to introduce effective bundle deals and increase average basket size for online transactions. By considering the recommendation system, customer segmentation, and sales performance of products, Decathlon Singapore can strategically implement bundle deals to drive sales volume and enhance turnover.

Business Insights and Recommendations will include personalized marketing campaigns, loyalty programs, and targeted promotions to engage different customer segments. Additionally, the stable and predictable market environment allows for optimized supply chain and inventory management.

By implementing the recommendations and conducting A/B testing, Decathlon can make informed decisions to improve customer satisfaction, increase sales, and drive business growth. Continuous monitoring and validation will be crucial to ensure the effectiveness of the bundle deals and maintain relevance in the market.
