# Requirement
In this report, we need to get the total films made by each actor, considering only actors that had made over 20 films

The output of the report should have the following:

Actor Full Name (First Name, Last Name)
Actor ID
Total Movies for this actor

# Applied Logic
```sql
SELECT a.first_name + ' ' + a.last_name AS actor_name, COUNT(fa.film_id) AS #_of_films
FROM actor a
JOIN film_actor fa ON(a.actor_id = fa.actor_id)
GROUP BY a.first_name + ' ' + a.last_name
HAVING COUNT(fa.film_id) > 20
ORDER BY 2 DESC;
```

## Package Creation: 

<img width="960" alt="image" src="https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/26c81b09-39aa-4635-812f-df328edd1c9e">


## Running Package

<img width="960" alt="image" src="https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/bc5f74bb-3108-4716-8035-f77474acb494">

