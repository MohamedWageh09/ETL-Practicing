# Requirement
In this report, we need to get the total films made by each actor, considering only actors that had made over 20 films

The output of the report should have the following:

Actor Full Name (First Name, Last Name)
Actor ID
Total Movies for this actor

# Applied Logic
select actor.first_name + ' ' + actor.last_name as "Full name",
actor.actor_id ,
count(film_actor.film_id) as "Total movies"
From actor
Join film_actor
on actor.actor_id = film_actor.actor_id
group by actor.first_name + ' ' + actor.last_name , actor.actor_id
having count(film_actor.film_id) > 20
order by count(film_actor.film_id) desc
