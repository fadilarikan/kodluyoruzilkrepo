# SQL Ödev 4

## 1. Sorunun Cevabı 

![answer4.1](./images/4.1.JPG)

```sql
SELECT DISTINCT replacement_cost 
FROM film;
```
## 2. Sorunun Cevabı 

![answer4.2](./images/4.2.JPG)

```sql
SELECT COUNT(DISTINCT replacement_cost) 
FROM film;
```

## 3. Sorunun Cevabı 

![answer4.3](./images/4.3.JPG)

```sql
SELECT COUNT(*) 
FROM film
WHERE title LIKE 'T%' AND rating = 'G';

```

## 4. Sorunun Cevabı 

![answer4.4](./images/4.4.JPG)

```sql
SELECT COUNT(*) 
FROM country 
WHERE country LIKE '_____';
```

## 5. Sorunun Cevabı 

![answer4.5](./images/4.5.JPG)

```sql
SELECT COUNT(*)
FROM city
WHERE city ILIKE '%r';
```