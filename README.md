**List the Products Ordered in a Period**

The Products table contains data about the company's products.
product_id is the primary key (column with unique values) for this table.

The Orders table contains product_id, order_date, and unit.
This table may have duplicate rows.
product_id is a foreign key (reference column) to the Products table.
unit is the number of products ordered in order_date.
Write a solution to get the names of products that have at least 100 units ordered in February 2020 and their amount.
Return the result table in any order.
