# A-B-Testing-Tale-of-Two-Campaigns

## Executive Summary

This project focused on an A/B testing case study comparing two digital marketing campaigns to determine which performed better in driving user engagement and purchases. I conducted a detailed analysis of key conversion metrics, performed statistical testing, and provided data-driven recommendations based on the insights. The test campaign demonstrated higher click-through and purchase rates, but the control campaign had a lower cost per purchase. Skills applied include A/B testing methodology, funnel analysis, and statistical testing using Python. The recommendation is to refine the Test Campaign to improve cost efficiency while leveraging the Control Campaign’s insights for product presentation and targeting strategies.

## Business Problem

The goal was to evaluate the performance of two marketing campaigns—Test Campaign and Control Campaign—to understand which one led to better user engagement (clicks, add-to-cart actions, purchases) and determine whether the Test Campaign’s improvements justify a potential higher ad spend. The business needs to know which campaign should be adopted moving forward to maximize ROI and reduce customer acquisition costs.

## Methodology

1. Data Preparation: Analyzed user interaction data from both campaigns, focusing on key metrics like impressions, clicks, add-to-cart actions, and purchases.
2. Funnel Analysis: Created a funnel chart to visualize how users moved from impressions to purchases in each campaign.
3. Conversion Rate Calculation: Calculated click-through rates (CTR), add-to-cart rates, and purchase rates to evaluate user engagement and purchasing behaviors.
4. Statistical Testing: Performed a two-sample t-test to validate whether the differences between the two campaigns were statistically significant.

## Skills

Python: Data analysis and manipulation (Pandas, NumPy), statistical testing (SciPy), and visualizations (Matplotlib, Seaborn).
A/B Testing: Conducted statistical hypothesis testing to compare the performance of two groups.
Funnel Analysis: Created visualizations to track user progression through key stages (Impressions → Clicks → Purchases).
Business Analytics: Extracted actionable insights from data to support decision-making.

## Results & Business Recommendation

Key Results:
1. The Test Campaign outperformed the Control Campaign in terms of overall click-through rate (10.24% vs. 4.96%) and purchase rate (61.79% vs. 46.33%).
2. The Control Campaign had a better add-to-cart rate (78.88% vs. 51.51%) and a lower cost per purchase ($4.32 vs. $4.92).
3. Statistical Testing: The two-sample t-test indicated no significant difference between the campaigns, meaning the higher performance of the Test Campaign did not reach statistical significance.

Business Recommendation:
1. Optimize the Test Campaign: It has potential but requires cost optimization to lower the cost per purchase.
2. Leverage Control Campaign Learnings: The higher add-to-cart rate in the Control Campaign suggests users were more motivated to add items to the cart, so refining the Test Campaign’s user journey could be a key improvement.
3. Next Steps: Consider further A/B testing on additional variables, such as ad creatives or targeting strategies, to boost performance while reducing costs.
   
## Next Steps

1. Refine Ad Creatives 📧: Conduct further testing to optimize the Test Campaign to reduce cost per purchase.
2. Explore New Targeting Strategies 🎯: Evaluate different audience segments or geographic targeting to improve efficiency.
3. Expand Analysis 📊: Investigate the impact of other engagement metrics, like time spent on site or product interactions, to gather more granular insights.

(Dataset Source: kaggle datasets download -d ilkeryildiz/example-dataset-for-ab-test)
