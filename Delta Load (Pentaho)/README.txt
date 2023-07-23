In this sales data i wanted to load the newly added products in the database and to do this i've done the following:

- First i've created a staging schema then added the products table and created a surrogate key then:
1) Created a transformation to select the maximum product id from products dimension
2) Created another transformation to filter and load the newly added data where the product_id is larger than the maximum
Then saved the job and tested it
