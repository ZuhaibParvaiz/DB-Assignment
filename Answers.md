# DB-Assignment
Ist ans: The relationship mapping between Product_Category and Product is One-To-Many where a particular product category will have multiple products but a product can be assigned to only a single product category only.

2nd ans: We can ensure that each product has a valid product category assigned to it by making changes to both tables.
In Product_Category:
i) make id as pk, not_null, unique.

In Product table:
i) make category_id not null.
