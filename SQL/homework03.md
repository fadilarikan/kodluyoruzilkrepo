# SQL Ödev 3

## 1. Sorunun Cevabı 

![answer3.1](./images/3.1.JPG)

```sql
SELECT country
FROM country
WHERE country LIKE 'A%a';
```
## 2. Sorunun Cevabı 

![answer3.2](./images/3.2.JPG)

```sql
SELECT country
FROM country
WHERE country LIKE '_____%n';
```

## 3. Sorunun Cevabı 

![answer3.3](./images/3.3.JPG)

```sql
SELECT *
FROM film
WHERE title ILIKE '%t%t%t%t%';

```

## 4. Sorunun Cevabı 

![answer3.4](./images/3.4.JPG)

```sql
SELECT *
FROM film
WHERE title LIKE 'C%' AND length > 90 AND rental_rate = 2.99;
```