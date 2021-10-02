# SQL Ödev 2

## 1. Sorunun Cevabı 

![answer2.1](./images/1.1.JPG)

```sql
SELECT *
FROM film
WHERE replacement_cost BETWEEN 12.99 AND 16.98;
```
## 2. Sorunun Cevabı 

![answer2.2](./images/2.2.JPG)

```sql
SELECT first_name,last_name
FROM actor
WHERE first_name IN ('Penelope','Nick','Ed');
```

## 3. Sorunun Cevabı 

![answer2.3](./images/2.3.JPG)

```sql
SELECT *
FROM film
WHERE rental_rate IN (0.99,2.99,4.99) AND replacement_cost IN (12.99,15.99,28.99);
```

