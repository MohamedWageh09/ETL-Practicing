# Requirement
In this report, we need to get the total revenue earned from each city, and we need the following details in the report:

City Name
Total Revenue Amount 

# Applied Logic:
````sql
SELECT c.city, SUM(p.amount) AS revenue
FROM payment p
JOIN customer cu ON(p.customer_id = cu.customer_id)
JOIN address a ON(cu.address_id = a.address_id)
JOIN city c ON(a.city_id = c.city_id)
GROUP BY c.city
ORDER BY revenue DESC;
````

## Package Creation:

<img width="960" alt="image" src="https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/6fff31b4-b413-4f29-a03b-b619b4e35789">

## Running Package:

<img width="960" alt="image" src="https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/2ed4ffc3-1302-4dc6-9d4d-348d17d1b113">




