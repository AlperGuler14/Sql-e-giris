# SQL Homework 03

## 1. Country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız.


```sql
SELECT country FROM country 
WHERE country LIKE 'A%a';
