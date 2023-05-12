# Customer-segmentation
## Introduction:
![image](https://github.com/Ziadashraf301/Customer-segmentation/assets/111798631/fc4f064d-b606-4270-9a0a-643cc186c1ee)
In this notebook, I will analyze and explore the purchase orders of customers from grocery stores to help the marketing department:
- Set their marketing goals.
- Identify the personas of the customer and target audiences.
- Get the best knowledge of their customer groups and behaviors.

## Main Questions:
These are the questions the marketing department wants answers to:
- What is the best segmentation for customers?
- What is the order status of different customer segments?
- What are the trends in the customer behavior segments over time?
- What are the insights from the RFM analysis?
- What are the best features for clustering customers?

## Main Goal :
- Increase customer loyalty and customer lifetime value. 
- Remarketing to groups that haven't bought anything or haven't bought in a long time.
- Increase new customer awareness and attraction.
- Establish relationships with customers who are in the conversion stage of the marketing funnel.

## Data collection:
We have data about the customers' purchase orders over time. So we will rely on the purchase history of each customer to get actionable insights.

### Data Set Information: 
The dataset has 38765 rows of purchase orders from customers at grocery stores. These orders can be analyzed using descriptive statistics, inference statistics, RFM analysis, and machine learning algorithms such as clustering (K-means).

### Features Information:
- Member Number: Nominal, a 4-digit integral number uniquely assigned to each member. 
- Item Description: Product Name (Nominal).
- Date: the day and time at which each transaction was generated.

## Data Understanding and Preparation:
Before I applied customer segmentation, I explored the data, prepared it, and understood it through:
- Check the data type.
- Check the missing values.
- Check the duplicate rows.
- Descriptive statistics (statistical exploration).
- Features extraction using the time factor.
- Distribution analysis.
- Grouping.
- RFM analysis.
- Correlation analysis.
- ANOVA.
- Transformation of variables (normalization and logarithmic transformation).
- PCA.
- Feature selection.

## K-means and business value
![image](https://github.com/Ziadashraf301/Customer-segmentation/assets/111798631/ad114a2a-fc7b-4004-a9fa-b2aa582854b8)
![image](https://github.com/Ziadashraf301/Customer-segmentation/assets/111798631/d4499d0a-f51f-4fae-b167-2f417b1e9964)

We can conclude that:
- The customer who purchased on Monday (the first day of the week) significantly has similar traits, habits, and lifestyles. We can participate in interviews or surveys with them to understand what caused them to purchase on the first day of the week. Maybe Sunday is a day of rest. So they stayed at home this day and consumed things, which caused them to go to the market the next day for shopping. It's also possible that customers who purchase on Monday do so because they have more free time on that day, or because they are preparing for the week ahead. Understanding these underlying factors can help the store tailor its marketing efforts and product offerings to better meet the needs of these customers. However, it's important to note that customers in this cluster may also be infrequent or one-time buyers, which could limit the potential for long-term engagement and loyalty. To address this, the store may need to implement retention strategies such as personalized offers, loyalty programs, or exceptional customer service to encourage these customers to continue doing business with the store.

- Customers who have low monetary and low-frequency values may be considered at risk of churning, which means they may stop doing business with the store in the future. This is because customers who have low spending habits and low engagement with the store may not see the value in continuing to purchase from the store and may prefer to purchase elsewhere. To better understand whether customers with low monetary and low-frequency values are at risk of churning, it may be helpful to examine additional factors, such as their engagement with the store's marketing campaigns or customer service interactions, through interviews or surveys. There are several strategies that the store can use to increase their engagement and encourage them to continue doing business with the store:

    - Targeted promotions: Offer personalized promotions or discounts to customers who have low monetary and low-frequency values. This can help to incentivize them to make a purchase and increase their engagement with the store.
 
    - Improve customer experience: Focus on providing exceptional customer service and a seamless customer experience to help build trust and loyalty with customers. This can encourage them to continue placing orders with the store, even if they have low monetary and low-frequency values.

    - Increase brand awareness: Increase the store's visibility and brand awareness through advertising, social media, and other marketing channels. This can help to attract new customers and increase engagement with existing ones, including those with low monetary and low-frequency values.

    - Loyalty programs: Consider implementing a loyalty program that incentivizes customers to make repeat purchases and increases their engagement with the store. This can help build customer loyalty and increase their lifetime value to the store.

- Customers who have high frequency and high monetary values may be more likely to have developed a sense of loyalty to the store. This is because they have demonstrated a sustained interest in the store's offerings and have invested a significant amount of money and time into their relationship with the store. However, it's important to note that loyalty is not guaranteed and should not be taken for granted. Even customers who have reached the loyalty stage of the marketing funnel can be at risk of churning if they experience a negative experience with the store or if they perceive that they are not receiving sufficient value from their relationship with the store. To maintain customer loyalty, it's important for the store to continue to provide high-quality products or services, personalized experiences, and exceptional customer service. Additionally, offering rewards programs or other incentives can help reinforce the customer's sense of loyalty and encourage them to continue doing business with the store.
