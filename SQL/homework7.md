# SQL Ödev 7

## 1. Sorunun Cevabı 

![answer7.1](./images/7.1.JPG)

```sql
SELECT title,rating
FROM film
GROUP BY title,rating
ORDER BY title;

```
## 2. Sorunun Cevabı 

![answer7.2](./images/7.2.JPG)

```sql
SELECT replacement_cost,COUNT(replacement_cost)
FROM film
GROUP BY replacement_cost
HAVING COUNT(replacement_cost) >50;

```

## 3. Sorunun Cevabı 

![answer7.3](./images/7.3.JPG)

```sql
SELECT store_id,COUNT(store_id)
FROM customer
GROUP BY store_id;



```

## 4. Sorunun Cevabı 

![answer7.4](./images/7.4.JPG)

```sql
SELECT country_id,COUNT(country_id)
FROM city
GROUP BY country_id
ORDER BY COUNT(country_id) DESC
LIMIT 1;

```