# **About Dataset**

# **Dataset Description: E-commerce Customer Behavior**

**Overview:**
  This dataset provides a comprehensive view of customer behavior within an e-commerce platform. Each entry in the dataset corresponds to a unique customer, offering a detailed breakdown of their interactions and transactions. The information is crafted to facilitate a nuanced analysis of customer preferences, engagement patterns, and satisfaction levels, aiding businesses in making data-driven decisions to enhance the customer experience.

**Columns:**

- **Customer ID:**
  **Type:** Numeric
  **Description:** A unique identifier assigned to each customer, ensuring distinction across the dataset.

- **Gender:**
**Type:** Categorical (Male, Female)
**Description:** Specifies the gender of the customer, allowing for gender-based analytics.

- **Age:**
**Type:** Numeric
**Description:** Represents the age of the customer, enabling age-group-specific insights.

- **City:**
**Type:** Categorical (City names)
**Description:** Indicates the city of residence for each customer, providing geographic insights.

- **Membership Type:**
**Type:** Categorical (Gold, Silver, Bronze)
**Description:** Identifies the type of membership held by the customer, influencing perks and benefits.

- **Total Spend:**
**Type:** Numeric
**Description:** Records the total monetary expenditure by the customer on the e-commerce platform.

- **Items Purchased:**
**Type:** Numeric
**Description:** Quantifies the total number of items purchased by the customer.

- **Average Rating:**
**Type:** Numeric (0 to 5, with decimals)
**Description:** Represents the average rating given by the customer for purchased items, gauging satisfaction.

- **Discount Applied:**
**Type:** Boolean (True, False)
**Description:** Indicates whether a discount was applied to the customer's purchase, influencing buying behavior.

- **Days Since Last Purchase:**
**Type:** Numeric
**Description:** Reflects the number of days elapsed since the customer's most recent purchase, aiding in retention analysis.

- **Satisfaction Level:**
**Type:** Categorical (Satisfied, Neutral, Unsatisfied)
**Description:** Captures the overall satisfaction level of the customer, providing a subjective measure of their experience.
---

**Use Cases:**

- **Customer Segmentation:**
Analyze and categorize customers based on demographics, spending habits, and satisfaction levels.

- **Satisfaction Analysis:**
Investigate factors influencing customer satisfaction and identify areas for improvement.

- **Promotion Strategy:**
Assess the impact of discounts on customer spending and tailor promotional strategies accordingly.

- **Retention Strategies:**
Develop targeted retention strategies by understanding the time gap since the last purchase.

- **City-based Insights:**
Explore regional variations in customer behavior to optimize marketing efforts based on location-specific trends.
---

## **Conclusion from the Exploratory Data Analysis**

The Exploratory Data Analysis (EDA) of e-commerce customer behavior dataset provides several insightful conclusions:

**Demographic Insights:**
- **Age Distribution:** A diverse range of customer ages, indicating a broad customer base. Gender Distribution: Variations in spending patterns between genders. This could be important for targeted marketing and product placement - strategies.

- **Total Spend:** Most customers have a specific spending range, with a few spending significantly higher. Items Purchased: A clear pattern in the number of items purchased, suggesting common purchasing behaviors among customers. High Correlation: Total spend is highly correlated with the number of items purchased, which implies that as customers buy more items, their total expenditure increases. Customer Preferences and Ratings:

- **Average Rating:** The distribution indicates how customers generally perceive the service or products. There is a notable correlation between total spend and average rating, suggesting that higher spending might be associated with higher satisfaction. Satisfaction Levels: Different satisfaction levels (Satisfied, Neutral, Unsatisfied) show distinct patterns in terms of spending, which can inform customer retention strategies. Geographical Influence:

- **City-Based Spending:** Variation in average spending across different cities indicates geographical influences on customer behavior. This can be useful for regional marketing strategies. Membership and Loyalty:

- **Membership Type:** Different types of memberships (Gold, Silver, Bronze) show distinct spending patterns. Notably, there's a strong correlation between having a Gold membership and being in the satisfied customer segment. Discounts and Purchasing Frequency:

- **Discount Applied:** The impact of discounts on customer spending and satisfaction levels. Days Since Last Purchase: This metric reveals purchase frequency and recency, which are crucial for understanding customer engagement and loyalty. Correlation Findings:

- **Highly Correlated Variables:** Identified pairs with strong positive or negative correlations. Low Correlated Variables: Identified pairs with weak correlations, indicating little to no linear relationship. Overall, this EDA provides a comprehensive understanding of the customer base, their spending habits, preferences, satisfaction levels, and how these aspects correlate with demographic and geographical factors. These insights can inform targeted marketing strategies, customer retention programs, product development, and predictive modeling for future customer behavior.

---
# **Conclusion:**

The e-commerce customer behavior analysis project provided valuable insights into different customer segments, their spending habits, and satisfaction levels. Through exploratory data analysis and customer segmentation using Logistic Regresssion, Decision Tree Classifier, three distinct customer groups were identified: younger high spenders with high satisfaction, middle-aged lower spenders with lower satisfaction, and young to middle-aged moderate spenders with moderate satisfaction. These findings suggest targeted marketing approaches for each segment, focusing on personalized experiences and product offerings. The project highlights the importance of understanding customer behavior in tailoring business strategies, with potential to enhance customer satisfaction, optimize product offerings, and improve overall business performance in the e-commerce sector.
