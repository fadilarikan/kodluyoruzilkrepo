# SQL Ödev 11

## 1. Sorunun Cevabı 

![answer11.1](./images/11.1.JPG)

```sql
(
SELECT first_name
FROM actor
)
UNION
(
SELECT first_name
FROM customer
);
```
## 2. Sorunun Cevabı 

![answer11.2](./images/11.2.JPG)

```sql
(
SELECT first_name
FROM actor
)
INTERSECT
(
SELECT first_name
FROM customer
);


```

## 3. Sorunun Cevabı 

![answer11.3](./images/11.3.JPG)

```sql
(
SELECT first_name
FROM actor
)
EXCEPT
(
SELECT first_name
FROM customer
);

```

## 4. Sorunun Cevabı 

![answer11.41](./images/11.41.JPG)

```sql
(
SELECT first_name
FROM actor
)
UNION ALL
(
SELECT first_name
FROM customer
);

```
![answer11.42](./images/11.42.JPG)

```sql
(
SELECT first_name
FROM actor
)
INTERSECT ALL
(
SELECT first_name
FROM customer
);

```
![answer11.43](./images/11.43.JPG)

```sql
(
SELECT first_name
FROM actor
)
EXCEPT ALL
(
SELECT first_name
FROM customer
);

```