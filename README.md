**Market Basket Analysis - Readme**

**Problem Statement:**
The merchandising team wishes to introduce bundle deals for all products on their website to increase the average basket size when customers make online purchases. The goal is to offer multiple products at a discounted price, encouraging higher sales volume and ultimately increasing turnover.

**Methodology:**
The analysis follows a three-pronged approach:
1. **Recommendation System:** Utilizing historic transaction data to identify products frequently purchased together or having high affinity. This helps in selecting suitable products for bundling.
2. **Customer Segmentation:** Segmenting the customer base based on demographics, purchase history, and preferences to identify unique preferences and behaviors. This guides in selecting the right products for each segment's bundling strategy.
3. **Sales of Underperforming Products:** Analyzing sales performance of individual products to identify underperforming items. Bundling these products with more popular ones can increase their visibility and sales potential.

**Analysis based on considerations:**
The recommendation system identifies popular pairings within the "Sports" and "Product Type" categories. For example, it may reveal that shorts are frequently purchased with other apparel, making them good candidates for bundling deals. Customer segmentation categorizes customers into High Value, Loyal, Churned, and Non-members. For each segment, popular product pairings are identified to tailor bundle deals accordingly.

**A/B Testing:**
Each bundle deal goes through a two-week A/B testing phase to evaluate its effectiveness. The key metric is the average sum of turnover generated during this period. Hypothesis testing is used to compare the performance of bundle deals to regular transactions. Statistical power analysis is conducted to assess the reliability of the results given the sample size.

**Implementation:**
Bundle deals are introduced to customers after they add an item to the cart. This prevents complicating the user journey while offering an additional option for increased sales. The experiment spans two weeks to avoid day-of-week effects and major events. A good mix of customers from each segment is considered to evaluate the impact on different spending habits.

**Launch Decision:**
After the experiment, the results are analyzed, and the null hypothesis is tested against the minimum detectable effect, superiority margin, and significance level. The cost of launching, including the discount per bundle, is considered for final decision-making.

**Limitations and Caveats:**
1. The analysis focuses on turnover as a metric, which can be influenced by high-priced items like bicycles. Normalizing turnover based on product price may offer more nuanced insights into popularity.
2. The analysis relies on broad category pairings; finer relationships between individual products could be explored for better bundling strategies.

**Business Insights:**
1. Based on the analysis, personalized marketing campaigns can be implemented using the recommendation system to target individual customers.
2. High-value members can be targeted with exclusive bundle deals and offers to boost loyalty and spending.
3. Underperforming products can be bundled with popular ones to boost sales and attract more customers.

**Readme Summary:**
The Market Basket Analysis uses a recommendation system, customer segmentation, and analysis of underperforming products to introduce effective bundle deals. A/B testing is conducted to evaluate the impact of the deals on average turnover. The analysis provides valuable insights for personalized marketing, customer targeting, and boosting sales of underperforming products.
