# Brainwave-Matrex-Solutions
superstore sales data analysis

Introduction: 

I collected this dataset from Kaggle ([https://www.kaggle.com/datasets/vivek468/superstore-dataset-final?select=Sample+-+Superstore.csv](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final?select=Sample+-+Superstore.csv)) 
which contains data for superstor sales.

data description:

1- Row ID => Unique ID for each row.
  
2- Order ID => Unique Order ID for each Customer.

3- Order Date => Order Date of the product.

4- Ship Date => Shipping Date of the Product.

5- Ship Mode=> Shipping Mode specified by the Customer.

6- Customer ID => Unique ID to identify each Customer.

7- Customer Name => Name of the Customer.

8- Segment => The segment where the Customer belongs.

9- Country => Country of residence of the Customer.

10- City => City of residence of of the Customer.

11- State => State of residence of the Customer.

12- Postal Code => Postal Code of every Customer.

13- Region => Region where the Customer belong.

14- Product ID => Unique ID of the Product.

15- Category => Category of the product ordered.

16- Sub-Category => Sub-Category of the product ordered.

17- Product Name => Name of the Product.

18- Sales => Sales of the Product.

19- Quantity => Quantity of the Product.

20- Discount => Discount provided.

21- Profit => Profit/Loss incurred.
  
== This report presents the results of a comprehensive analysis conducted on department store sales data. The primary objective of this analysis was to understand sales performance, profitability, and customer loyalty, and to identify key trends and patterns within the dataset.

- Data Summarization and Cleaning

The presented dataset underwent a comprehensive inspection and cleaning process.
The cleaning steps included:

1- I checked the data and it was free of duplicates and missing data

2- (Delete unnecessary Columns): I removed columns such as Row ID and Postal Code because they were not necessary for analysis.

3- (Data Type Conversion): I converted data types for columns such as Order Date and Shipped Date to DateTime objects, and converted classification columns to the Category type.

== EDA:

Sales:

1- The average sales value was approximately 229.86.

2- Sales values ​​varied widely, ranging from a minimum of 0.44 to a maximum of 22638.48.

3- A high standard deviation (623.25) indicates a wide variation in sales values.

Quantity:

1- The average quantity ordered was approximately 3.79 units.

2- Most orders contained small quantities, with 75% of orders containing 5 units or less.

Discount:

1- The average discount value was approximately 16%.

2- Common discount values ​​appeared to be 0% and 20%.

Profit:

1- The average profit was approximately 28.66.
2- Profit values ​​varied widely, including losses as large as -6599.98 and gains as large as 8399.98.
13- The large standard deviation of profit (234.26) indicates a large variance in profit values.

- Porpose of the analysis:
- 
1- What are the best-selling categories and products?

2- Which categories and products generate the highest profits? Are there any products that generate losses?

3- Which geographic regions/states generate the highest sales and profits?

4- What is the relationship between discounts and profits? Do large discounts always lead to losses?

5- How are sales distributed over time? Are there seasons or months that experience higher sales?

6- How do different shipping channels (ship modes) perform in terms of sales and profits?

7- Is there a relationship between order date and ship date and profitability or customer satisfaction?

- Key Findings

(Top Selling Products):

Categories: The Office Supplies category recorded the highest sales volume, followed by Furniture, and Technology.

Products: Among the best-selling individual products were Staples, Staple Envelopes, and Easy Staple Paper.

Profitability Analysis:
 
Categories: The "Technology" category generated the highest overall profit, followed by "Office Supplies," while the "Furniture" category generated relatively lower profits.
Profitable Products: Products such as the "Canon imageCLASS 2200 High-End Copy Machine" and the "Fellowes PB500 Electric Binding Machine with Plastic Comb" were among the most profitable.
Losing Products: The most notable products that incurred significant losses were the Cubify CubeX dual-head 3D printer and the GBC DocuBind P400 electric binding system.

Discount Relationship to Profit:
I observed a weak negative correlation (-0.22) between discounts and profits, indicating that higher discounts are typically associated with lower profits, although their impact is not significant.
922 transactions with discounts of 50% or more resulted in losses.

(the best region making profit):

1- The West region is the most profitable region, with a total profit of 108,418.45.

2- The East region is second, with a total profit of 91,522.79.

3- The South region is third, with a total profit of 46,749.43.

4- Finally, the Central region is the least profitable, with a total profit of 39,706.36.

Summary:

The West and East regions are the major contributors to profits, while the Central region generates the least profit of the four regions. This information can be used to make strategic decisions such as allocating resources or better targeting marketing campaigns.

 Sales over time:
 
Analyzing sales trends over time (2014-2017) revealed a general upward trend in sales.
Seasonal fluctuations were evident, with sales typically peaking at the end of each year (November/December) and declining at the beginning of the year (January/February).

Shipping Channel Performance:

The "Standard Class" shipping channel recorded the highest sales and overall profits.

The "Same Day" shipping channel recorded the lowest sales and profits.

Delivery Time and Profitability:

I calculated average profit for different delivery times. Initial analysis did not reveal a clear and direct pattern between delivery time and profitability, which warrants a more in-depth investigation.

Most Loyal Customers:

Based on the number of orders placed, customer ID "EP-13919" was identified as the most loyal, with a total of 17 orders. Several other customers also displayed a high number of orders.

 Conclusions and Recommendations:

1. Focus on maximizing sales of the most profitable categories and products, such as "technology" and specific products within "office supplies."
2. Conduct a comprehensive analysis of losing products to determine whether they should be discontinued or strategies implemented to improve their profitability.
3. Leverage high-performing regions and states through targeted marketing campaigns.

4. Study the impact of deep discounts on profitability in greater depth to develop optimal pricing strategies.
5. Leverage specific seasonal sales patterns for inventory planning and promotional activities.
6. Evaluate the performance and costs associated with various shipping channels to enhance efficiency and profitability.
7. Develop customer loyalty programs that target repeat customers to enhance retention and increase spending.
