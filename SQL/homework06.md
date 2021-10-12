# SQL Ödev 6

## 1. Sorunun Cevabı 

![answer6.1](./images/6.1.JPG)

```sql
SELECT ROUND(AVG(rental_rate),2)
FROM film;
```
## 2. Sorunun Cevabı 

![answer6.2](./images/6.2.JPG)

```sql
SELECT COUNT(*)
FROM film
WHERE title LIKE 'C%';
```

## 3. Sorunun Cevabı 

![answer6.3](./images/6.3.JPG)

```sql
SELECT MAX(length)
FROM film
WHERE rental_rate = 0.99;


```

## 4. Sorunun Cevabı 

![answer6.4](./images/6.4.JPG)

```sql
SELECT COUNT(DISTINCT(rental_rate))
FROM film
WHERE length > 150;


```