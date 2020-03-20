Heroku Laravel 5.6 deploy 
We have 4 tables - products, report, report_views and users.
Table Products contains the information about the product.
Table Report contains the amount and quantity of products purchased.
Table Report_views contains the quantity of views of any product by specific user.
Table Users contains users.

1. Please form the needed relationships between the modeles:
- products > report
- products > report_views
- report > products
- report_views > products

2. Сreate relation one to many between the tables Users and Report_views . Create a controller where you have to form a request to the model User and the model Report_views that is related to it. Please use eager loading.

3. Please create a table (html) where show the result for a specific date. It should contain product Id, product name, overall amount of purchase of some product, overall number of views of the specific product. Write for it only one SQL query. For starting please use select with the dates - you should show the result by choosing any date. User API routes.

4. Please create a table that contains product Id and percentage of purchases number depending on views quantity. Please write for it only one SQL request and don't do any additional calculations with PHP or JS help. All calculations should be done with SQL.
