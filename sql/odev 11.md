# SQL Homework 11

## 1.actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.

```sql
(
SELECT first_name FROM actor
)
UNION
(
 SELECT first_name FROM customer
);
```
## 2.actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım.

```sql
(
SELECT first_name FROM actor
)
INTERSECT
(
 SELECT first_name FROM customer
);
```

## 3.actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.
```sql
(
SELECT first_name FROM actor
)
EXCEPT
(
SELECT first_name FROM customer
);
```

## 4.İlk 3 sorguyu tekrar eden veriler için de yapalım.

```sql
        (SELECT first_name FROM actor
        ORDER BY first_name)
        UNION ALL
        (SELECT first_name FROM customer
        ORDER BY first_name);

        (SELECT first_name FROM actor
        ORDER BY first_name)
        INTERSECT ALL
        (SELECT first_name FROM customer
        ORDER BY first_name);

        (SELECT first_name FROM actor
        ORDER BY first_name)
        EXCEPT ALL
        (SELECT first_name FROM actor
        ORDER BY first_name);
```
  
