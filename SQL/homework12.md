# SQL Ödev 12

## 1. Sorunun Cevabı 

![answer12.1](./images/12.1.JPG)

```sql
SELECT COUNT(title)
FROM film
WHERE length > (
SELECT AVG(length)
FROM film
);

```
## 2. Sorunun Cevabı 

![answer12.2](./images/12.2.JPG)

```sql
SELECT COUNT(title)
FROM film
WHERE rental_rate = (
SELECT MAX(rental_rate)
FROM film
);


```

## 3. Sorunun Cevabı 

![answer12.3](./images/12.3.JPG)

```sql
SELECT title
FROM film
WHERE rental_rate = (
SELECT MIN(rental_rate)
FROM film
) AND replacement_cost = (
SELECT MIN(replacement_cost)
FROM film
);


```

## 4. Sorunun Cevabı 

![answer12.4](./images/12.4.JPG)

```sql
SELECT customer_id, COUNT(amount) 
FROM payment
GROUP BY customer_id
ORDER BY COUNT(amount) DESC;



```