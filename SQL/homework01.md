# SQL Ödev 1

## 1. Sorunun Cevabı 

![answer1](./images/1.1.JPG)

```sql
SELECT title, description
FROM film
```
## 2. Sorunun Cevabı 

![answer2](./images/1.2.JPG)

```sql
SELECT *
FROM film
WHERE length > 60 AND length < 75;
```

## 3. Sorunun Cevabı 

![answer3](./images/1.3.JPG)

```sql
SELECT *
FROM film
WHERE rental_rate = 0.99 AND replacement_cost = 12.99 OR replacement_cost = 28.99;
```

## 4. Sorunun cevabı 

![answer4](./images/1.4.JPG)

```sql
SELECT last_name
FROM customer
WHERE first_name = 'Mary';
```

## 5. Sorunun cevabı 

![answer5](./images/1.5.JPG)

```sql
SELECT *
FROM film
WHERE NOT (length > 50 AND rental_rate = 2.99 OR rental_rate = 4.99);
```



