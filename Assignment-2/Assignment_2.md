# BETWEEN & IN
## Perform the following query scenarios on the ***dvdrental*** sample database.

1. Sort the data in all columns in the film table provided that the replacement cost value is greater than 12.99, equal and less than 16.99 (use **BETWEEN** - **AND** structure).
```sql
SELECT * FROM film
WHERE replacement_cost BETWEEN 12.99 AND 16.98;
```
![1](assets/1.png)

2. Sort the data in the ***first_name*** and ***last_name*** columns in the actor table provided that ***first_name*** is 'Penelope' or 'Nick' or 'Ed'. (Use the **IN** operator.)
```sql
SELECT first_name, last_name FROM actor
WHERE first_name IN ('Penelope', 'Nick', 'Ed');
```
![2](assets/2.png)

3. Sort the data in all columns in the film table with ***rental_rate*** 0.99, 2.99, 4.99 **AND** ***replacement_cost*** 12.99, 15.99, 28.99. (Use the **IN** operator.)
```sql
SELECT * FROM film
WHERE (rental_rate IN (0.99, 2.99, 4.99))
AND (replacement_cost IN (12.99, 15.99, 28.99));
```
![3](assets/3.png)
