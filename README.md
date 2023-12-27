# Axon Car Sales Data Analysis

## Business Problem

Axon, a small company specializing in classic car sales, faces challenges organizing and understanding their sales data. This analysis aims to assist Axon using tools such as Microsoft PowerBI and SQL to manage and analyze their sales information. The "Classicmodels" dataset, encompassing details about customers, employees, products, and order information, is utilized to create insightful reports for better decision-making.

## Proposal

Axon shared three years' worth of data, including details about orders, sales, customers, employees, and offices. The proposed solution involves:

1. **MySQL Database Setup:**
   - Create a MySQL database named "Classicmodels."
   - Download the data file [here](https://drive.google.com/file/d/1OB_iGw6vVS5KS7QwiwVChbeTfR4WvUy3/view?usp=share_link) and load it into MySQL.

2. **Data Exploration using MySQL:**
   - Analyze the entity-relationship diagram (ERR) to understand the database structure and relationships between tables.

3. **Data Cleaning:**
   - Utilize Power Query Editor in PowerBI for:
      - Renaming columns.
      - Removing unnecessary columns.
      - Merging columns where needed.
      - Replacing null and incorrect values.

4. **Data Transformation & Creating Dashboards:**
   - In PowerBI, create measures and insights from various perspectives, including customer, finance, product, and employee views.
     Certainly! Here are the measure names without detailed descriptions:
     
### Creating Measures

1. Total Customers
2. Total Payment
3. Total Orders
4. Average Order
5. Total Sales
6. Average Credit Limit
7. Average Credit Utilization
8. Total Cost
9. Total Profit
10. Average Order Value
11. Sales Growth Rate
12. Profit Margin
13. Average Order Processing
14. Order Fulfillment Time


## Insights from the Dashboard

### Customer View
- Highest number of customers in the USA.
- Euro+ Shopping has the highest number of orders and sales.
- Average payment per customer increased from October to November, with a subsequent dip.
- Average orders per customer are approximately 3.

### Finance View
- Classic cars are the most profitable product line.
- Trains are the least profitable.
- Total orders decreased in 2005 compared to 2003.
- USA contributes the maximum revenue.
- Sales and profits decreased in November and December.

### Product View
- '1992 Ferrari 360 Spider Red' is the most profitable product.
- Motorcycles have a higher profit margin than classic cars.

### Employee View
- Average order processing time is around 4 days.
- Paris has the highest number of sales.
- San Francisco city has the highest number of employees.

## Suggestions for Sales Improvement

- Consider cost-cutting in advertising in the North America region, where orders are already high.
- Implement training and reward programs to improve employee performance.
