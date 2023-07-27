# Requirement
In this report, we need to get the total films made by each actor, considering only actors that had made over 20 films

The output of the report should have the following:

Actor Full Name (First Name, Last Name)
Actor ID
Total Movies for this actor

# Applied Logic
```sql
SELECT a.first_name + ' ' + a.last_name AS actor_name, COUNT(f.film_id) AS #_of_films
FROM actor a
JOIN film_actor fa ON(a.actor_id = fa.actor_id)
JOIN film f ON (f.film_id = fa.actor_id)
GROUP BY a.first_name + ' ' + a.last_name
HAVING COUNT(f.film_id) > 20
ORDER BY 2 DESC;
```
