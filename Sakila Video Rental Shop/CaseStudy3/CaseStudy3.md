# Requirement
In this report, we need to get the details for each transaction, and generate a report that has the following details:

Movie Title
Amount paid for rent
Payment Date
Customer ID

# Applied Logic:
````sql
SELECT f.title AS movie_name, p.amount AS amount_paid, p.payment_date, p.customer_id
FROM payment p
JOIN rental r ON(p.rental_id = r.rental_id)
JOIN inventory i ON(r.inventory_id = i.inventory_id)
JOIN film f ON(i.film_id = f.film_id);
````

## Package Creation:

<img width="960" alt="image" src="https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/9ee8ab66-d493-4e31-9ce7-4d5fe03a46d1">

## Running Package:

<img width="960" alt="image" src="https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/68b24a0b-a160-42a0-8384-f2ea1039c438">




