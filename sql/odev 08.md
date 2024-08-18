# SQL Homework 07

## 1.Test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

```sql
CREATE TABLE employee (
	
	id SERIAL PRIMARY KEY ,
    name VARCHAR(50) NOT null,
	birthday DATE NOT null , 
	email VARCHAR(100) NOT null
);
```
## 2.Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim
```sql
insert into employee (name, birthday, email) values ('Roana', '1927-12-15', 'rklimsch0@spiegel.de');
insert into employee (name, birthday, email) values ('Elisha', '1964-12-10', 'ebleakley1@printfriendly.com');
insert into employee (name, birthday, email) values ('Elwira', '1951-08-28', 'edobbson2@loc.gov');
insert into employee (name, birthday, email) values ('Rudolf', '1996-10-16', 'rmacarthur3@php.net');
insert into employee (name, birthday, email) values ('Dosi', '1995-05-24', 'dmckerton4@yandex.ru');
insert into employee (name, birthday, email) values ('Stesha', '1984-02-09', 'sandrin5@dedecms.com');
insert into employee (name, birthday, email) values ('Ernie', '1979-04-07', 'eattenborough6@multiply.com');
insert into employee (name, birthday, email) values ('Randi', '1945-08-12', 'rdelafoy7@youtube.com');
insert into employee (name, birthday, email) values ('Justus', '1976-05-09', 'jgoacher8@amazonaws.com');
insert into employee (name, birthday, email) values ('Harv', '1924-12-27', 'hwintle9@lulu.com');
insert into employee (name, birthday, email) values ('Osgood', '1994-09-28', 'okempstona@surveymonkey.com');
insert into employee (name, birthday, email) values ('Bridgette', '1954-12-01', 'bmedwayb@dailymotion.com');
insert into employee (name, birthday, email) values ('Kerri', '1920-12-25', 'kminchic@bizjournals.com');
insert into employee (name, birthday, email) values ('Cynthy', '1957-06-23', 'cstaniforthd@wsj.com');
insert into employee (name, birthday, email) values ('Ingelbert', '1952-11-24', 'imcnesse@g.co');
insert into employee (name, birthday, email) values ('Angelique', '1958-02-28', 'averseyf@wiley.com');
insert into employee (name, birthday, email) values ('Rebeka', '1940-01-30', 'rdeblasiisg@newsvine.com');
insert into employee (name, birthday, email) values ('Idell', '1920-09-01', 'ichicchellih@paginegialle.it');
insert into employee (name, birthday, email) values ('Gayelord', '1993-02-15', 'ghoutbyi@senate.gov');
insert into employee (name, birthday, email) values ('Lotta', '1916-01-27', 'lantrumj@freewebs.com');
insert into employee (name, birthday, email) values ('Moise', '1901-05-07', 'mbinnellk@hostgator.com');
insert into employee (name, birthday, email) values ('Agnes', '1957-09-30', 'arapol@biblegateway.com');
insert into employee (name, birthday, email) values ('Coralie', '1923-09-14', 'creadwoodm@census.gov');
insert into employee (name, birthday, email) values ('Andonis', '1915-05-01', 'asimoneschin@google.nl');
insert into employee (name, birthday, email) values ('Jackie', '1937-03-12', 'jdoudnyo@abc.net.au');
insert into employee (name, birthday, email) values ('Dion', '1903-03-03', 'dmcnicklep@feedburner.com');
insert into employee (name, birthday, email) values ('Dacy', '1937-08-16', 'dgiamelliq@kickstarter.com');
insert into employee (name, birthday, email) values ('Bianca', '1923-06-17', 'bfolbiger@weebly.com');
insert into employee (name, birthday, email) values ('Camila', '1938-04-22', 'cstambridges@taobao.com');
insert into employee (name, birthday, email) values ('Joey', '1928-05-19', 'jalpheget@sogou.com');
insert into employee (name, birthday, email) values ('Merci', '1981-10-08', 'mcordelleu@artisteer.com');
insert into employee (name, birthday, email) values ('Rosette', '1937-09-12', 'rmcguggyv@last.fm');
insert into employee (name, birthday, email) values ('Rockie', '1926-08-09', 'royleyw@imgur.com');
insert into employee (name, birthday, email) values ('Codee', '1980-06-11', 'claphamx@cpanel.net');
insert into employee (name, birthday, email) values ('Isidor', '1952-10-06', 'ileinwebery@usatoday.com');
insert into employee (name, birthday, email) values ('Dorey', '1928-03-31', 'dmaccriez@sciencedirect.com');
insert into employee (name, birthday, email) values ('Yoshiko', '1980-05-29', 'yvauter10@nationalgeographic.com');
insert into employee (name, birthday, email) values ('Sandye', '1978-02-15', 'sdargan11@thetimes.co.uk');
insert into employee (name, birthday, email) values ('Sidoney', '1922-10-19', 'sromao12@forbes.com');
insert into employee (name, birthday, email) values ('Maurizia', '1924-03-13', 'mwellen13@ed.gov');
insert into employee (name, birthday, email) values ('Charmion', '1920-08-14', 'cgouldbourn14@discovery.com');
insert into employee (name, birthday, email) values ('Roxanna', '1945-09-25', 'rsnugg15@army.mil');
insert into employee (name, birthday, email) values ('Mathilda', '1913-03-28', 'mmacaskill16@themeforest.net');
insert into employee (name, birthday, email) values ('Callie', '1945-12-26', 'ckitlee17@nymag.com');
insert into employee (name, birthday, email) values ('Emory', '1908-11-16', 'estell18@fotki.com');
insert into employee (name, birthday, email) values ('Dick', '1924-08-02', 'ddumblton19@huffingtonpost.com');
insert into employee (name, birthday, email) values ('Lenee', '1965-03-07', 'ledmonson1a@wordpress.com');
insert into employee (name, birthday, email) values ('Frasquito', '1963-12-26', 'flucchi1b@biglobe.ne.jp');
insert into employee (name, birthday, email) values ('Doralia', '1975-09-12', 'dwasselin1c@slate.com');
insert into employee (name, birthday, email) values ('Rik', '1922-05-28', 'rcarruth1d@tumblr.com');
```
## 3.Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

```sql
UPDATE employee SET  name = 'UPDATE'
WHERE id =8
RETURNING *;

UPDATE employee SET name = 'UPDATE'
WHERE id =28
RETURNING *;

UPDATE employee SET name = 'UPDATE'
WHERE id =32
RETURNING *;

UPDATE employee SET name = 'UPDATE'
WHERE id =42
RETURNING*;

UPDATE employee SET name = 'UPDATE'
WHERE id =45
RETURNING*;
```

## 4.Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
```sql
DELETE FROM employee
WHERE id = 9
RETURNING * ; 

DELETE FROM employee
WHERE id = 10
RETURNING * ;

DELETE FROM employee
WHERE id = 11
RETURNING * ;

DELETE FROM employee
WHERE id = 12
RETURNING * ;

DELETE FROM employee
WHERE id = 13
RETURNING * ;
```
