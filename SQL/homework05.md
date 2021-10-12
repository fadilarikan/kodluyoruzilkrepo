# SQL Ödev 5

## 1. Sorunun Cevabı 

![answer5.1](./images/5.1.JPG)

```sql
SELECT * 
FROM film
WHERE title LIKE '%n' 
ORDER BY length DESC
LIMIT 5;
```
## 2. Sorunun Cevabı 

![answer5.2](./images/5.2.JPG)

```sql
SELECT * 
FROM film
WHERE title LIKE '%n' 
ORDER BY length ASC
OFFSET 5
LIMIT 5;
```

## 3. Sorunun Cevabı 

![answer5.3](./images/5.3.JPG)

```sql
SELECT * 
FROM customer
WHERE store_id = 1
ORDER BY last_name DESC
LIMIT 4;

```
