# ![Logo](https://github.com/Speardrex/Indian-General-Elections-2024-SQL/blob/main/Screenshot%202025-08-12%20224046.png)  **Indian General Elections 2024 SQL Project**
## Project Overview
## Database Schema

The project uses five main tables:

1. **Constituencywise Results**: Contains information about constituencywise results.
   - `Parliament Constituency`: Unique identifier for each constituency.
   - `Constituency Name`: Name of the Constituency.
   - `Winning Candidate`: Person who got elected.
   - `Total Votes`: Number of votes gained.
   - `Margin`: Won by the number of votes.
   - `Constituency ID`: Unique identifier for each constituency.
   - `Party ID`: Unique identifier for each party.

2. **category**: Holds product category information.
   - `category_id`: Unique identifier for each product category.
   - `category_name`: Name of the category.

3. **products**: Details about Apple products.
   - `product_id`: Unique identifier for each product.
   - `product_name`: Name of the product.
   - `category_id`: References the category table.
   - `launch_date`: Date when the product was launched.
   - `price`: Price of the product.

4. **sales**: Stores sales transactions.
   - `sale_id`: Unique identifier for each sale.
   - `sale_date`: Date of the sale.
   - `store_id`: References the store table.
   - `product_id`: References the product table.
   - `quantity`: Number of units sold.

5. **warranty**: Contains information about warranty claims.
   - `claim_id`: Unique identifier for each warranty claim.
   - `claim_date`: Date the claim was made.
   - `sale_id`: References the sales table.
   - `repair_status`: Status of the warranty claim (e.g., Paid Repaired, Warranty Void).
