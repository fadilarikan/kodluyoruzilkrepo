# SQL Ödev 9

## 1. Sorunun Cevabı 

![answer9.1](./images/9.1.JPG)

```sql
SELECT city,country
FROM city
JOIN country ON city.country_id = country.country_id;

```
## 2. Sorunun Cevabı 

![answer9.2](./images/9.2.JPG)

```sql
SELECT payment_id,first_name,last_name
FROM customer
INNER JOIN payment ON customer.customer_id = payment.customer_id;

```

## 3. Sorunun Cevabı 

![answer9.3](./images/9.3.JPG)

```sql
SELECT rental_id,first_name,last_name
FROM customer
INNER JOIN rental ON customer.customer_id = rental.customer_id;

```
