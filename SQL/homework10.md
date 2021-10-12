# SQL Ödev 10

## 1. Sorunun Cevabı 

![answer10.1](./images/10.1.JPG)

```sql
SELECT city,country
FROM city
LEFT JOIN country ON city.country_id = country.country_id; 
```
## 2. Sorunun Cevabı 

![answer10.2](./images/10.2.JPG)

```sql
SELECT payment_id,first_name,last_name
FROM customer
RIGHT JOIN payment ON customer.customer_id = payment.customer_id; 


```

## 3. Sorunun Cevabı 

![answer10.3](./images/10.3.JPG)

```sql
SELECT rental_id,first_name,last_name
FROM customer
FULL JOIN rental ON customer.customer_id = rental.customer_id; 

```
