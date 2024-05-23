# Enhancing-E-Commerce-Strategies-Using-Tableau

## Objective

In this project we have two pivotal datasets: 'Ecommerce Orders' and 'Customer Profiles'. The 'Ecommerce Orders' dataset offers detailed insights into customer orders, including products purchased, quantities, unit prices, order dates, and shipping costs. Meanwhile, the 'Customer Profiles' dataset provides rich information on customer demographics, such as email, country, membership type, and spending history.
Your mission is to utilize Tableau's robust capabilities to craft a compelling narrative from the provided datasets. This task will encompass thorough data preparation, intelligent data modeling, and the skillful application of calculated fields and Tableau functions for sophisticated analysis. The ultimate aim is to construct an interactive and intuitive dashboard in Tableau that showcases your key discoveries, offering concise, actionable insights into the optimization of hotel operations and performance.

![Screenshot 2024-05-23 231950](https://github.com/kiranahire03/Enhancing-E-Commerce-Strategies-Using-Tableau/assets/96494463/32b8293c-6c3b-436d-bf31-066bc07e4555)

## Data Source

The **"EcommerceDataset1.xlsx"** file contains the following columns:

1. **OrderID**: A unique identifier for each order.
2. **CustomerName**: Name of the customer.
3. **Product**: Type of product ordered.
4. **Quantity**: Quantity of the product ordered.
5. **UnitPrice**: Price per unit of the product.
6. **OrderDate**: Date when the order was placed.
7. **ShippingCost**: Cost of shipping for the order.
8. **CustomerID**: A unique identifier for each customer.  (Primary Key)

The **"EcommerceDataset2.xlsx"** file contains the following columns:

1. **CustomerID**: A unique identifier for each customer, corresponding to the 'CustomerID' in "EcommerceDataset1.xlsx". (Foreign Key)
2. **CustomerEmail**: Email address of the customer.
3. **Country**: Country of the customer.
4. **Membership**: Membership status of the customer (e.g., Premium, VIP).
5. **SignUpDate**: Date when the customer signed up.
6. **LastOrderDate**: Date of the customer's last order.
7. **TotalSpent**: Total amount spent by the customer.
8. **Customer Communication Log:** Detailed communication logs for each customer.

## Analysis Steps

### Part 1: Data Cleaning, Modeling, and Advanced Analysis in Tableau

2. **Customer Segmentation**: Segment customers based on their 'TotalSpent' into categories like 'High Spender', 'Medium Spender', 'Low Spender'. Define the thresholds for these categories.
3. **Calculated Field for Profit Margin**: Create a calculated field to estimate the profit margin per order. Assume a fixed percentage margin on the 'UnitPrice'.
4. **Analysis of Membership Types**: Analyze the distribution of orders across different 'Membership' types. Do certain membership types tend to spend more?
5. **Country-Based Analysis**: Compare the average order value and total quantity ordered by customers from different 'Countries'.
6. **Order Frequency Analysis**: Calculate the frequency of orders per customer. Who are the top repeat customers?
7. **Product Popularity Analysis**: Identify the most and least popular products based on the quantity ordered.
8. **Cohort Analysis**: Perform a cohort analysis based on the 'SignUpDate' of customers. How does the spending behavior vary among different cohorts?
9. **Dynamic Date Filters for Order Analysis**: Implement dynamic date filters to analyze order data over different timeframes.
10. **Customer Tenure Calculation**: Calculate the tenure of each customer from their 'SignUpDate' to the current date.
11. **Time-Series Analysis of Orders**: Analyze the trend of orders over time. Are there noticeable seasonal effects or trends?

### Part 2: Dashboard Building 

comprehensive dashboard in Tableau that includes visuals for total sales, order trends, customer spending patterns, and product popularity. Include filters for country, membership, and product type.

### Key Insights:

1. **Membership Distribution:** The distribution of memberships among customers is relatively balanced, with 32.80% classified as VIP members, 33.69% as Standard members, and 33.51% as Premium members.

2. **Customer Segmentation:** Segmentation based on Spending reveals that High Spenders constitute 49.55%, Medium Spenders make up 39.39%, and Low Spenders represent 11.05% of customers.

3. **Quarterly Customer Count:** The count of customers per quarter from Q1 2023 to Q3 2025 shows a peak at 84 customers in Q1 2023, with subsequent quarters ranging between 78 and 83 customers.

4. **Product Popularity:** 'Shirt' is the most popular product with 504 units ordered, while 'Bike' is the least popular with 420 units ordered.

5. **Product Combinations**: 'Laptop and Book' is the most common combination with 49 orders, while "Toy and Bike" is the least common with 29 orders.

6. **Shipping Costs Analysis:** Shipping costs vary inversely with the size or weight of items, showing a descending trend from bikes to toys. The average cost of shipping a Bike is $53.95, whereas for a Toy, it is $47.93.

7. **Order Trends:** Weekly orders average around 187, monthly orders around 82, and quarterly orders around 7.

8. **Customer Feedback Analysis:** High spenders have an average of 70 entries across complaints, feedback, inquiries, and requests, followed by medium spenders with 55 entries and low spenders with 15 entries.


