**The dataset contains 113,036 entries and 18 columns. Here's a brief overview of the columns:**

Date: The date of the transaction.
Day: The day of the transaction.
Month: The month of the transaction.
Year: The year of the transaction.
Customer_Age: The age of the customer.
Age_Group: The age group of the customer.
Customer_Gender: The gender of the customer.
Country: The country of the customer.
State: The state of the customer.
Product_Category: The category of the product.
Sub_Category: The sub-category of the product.
Product: The specific product.
Order_Quantity: The quantity of the product ordered.
Unit_Cost: The cost per unit of the product.
Unit_Price: The price per unit of the product.
Profit: The profit made on the transaction.
Cost: The total cost of the transaction.
Revenue: The total revenue from the transaction.


**Entities and Relationships**
Customer:

Attributes: Customer_Age, Age_Group, Customer_Gender, Country, State
Product:

Attributes: Product_Category, Sub_Category, Product, Unit_Cost, Unit_Price
Sales:

Attributes: Date, Day, Month, Year, Order_Quantity, Profit, Cost, Revenue
Relationships:
Customer places Sales
Product is included in Sales
ER Diagram Description
Customer (Customer_ID, Customer_Age, Age_Group, Customer_Gender, Country, State)

Customer_ID: Primary Key
Customer_Age: Integer
Age_Group: String
Customer_Gender: String
Country: String
State: String
Product (Product_ID, Product_Category, Sub_Category, Product, Unit_Cost, Unit_Price)

Product_ID: Primary Key
Product_Category: String
Sub_Category: String
Product: String
Unit_Cost: Integer
Unit_Price: Integer
Sales (Sales_ID, Date, Day, Month, Year, Order_Quantity, Profit, Cost, Revenue, Customer_ID, Product_ID)

Sales_ID: Primary Key
Date: Date
Day: Integer
Month: String
Year: Integer
Order_Quantity: Integer
Profit: Integer
Cost: Integer
Revenue: Integer
Customer_ID: Foreign Key
Product_ID: Foreign Key


**OUTCOME OF THE ANALYSIS**

# Conclusion:

# Unit Cost: The unit cost of products varies significantly, with a right-skewed distribution. 
#             This suggests that most products have a lower unit cost, but there are a few outliers with very high costs.

# Age Group: Adults (35-64) are the largest customer segment, indicating a potential target demographic for marketing efforts.

# Correlation: There is a positive correlation between cost and profit, suggesting that higher-cost items tend to yield higher profits.

# Country: Sales data from Canada might indicate a strong market presence in that region.

# Age Group and Unit Cost: The box plot reveals that different age groups have varying preferences for products with different unit costs.

# Average Profit by Country: The bar chart shows that average profit varies across different countries, highlighting potential areas for business expansion or optimization.

# Sales by Product Category: The pie chart illustrates the distribution of sales across product categories, providing insights into popular product lines.
