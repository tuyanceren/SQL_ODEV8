# SQL_ODEV8
**Patika SQL eğitimi kapsamında yaptığım ödev8**
-------------
1._test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım._
```sql
CREATE TABLE employee (
	id INTEGER,
	name VARCHAR(50) NOT NULL,
	email VARCHAR(100),
	birthday DATE 
);
```
2._Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim._
[Mockroo](https://www.mockaroo.com) ya tıklayarak sizde kendi tablonuzu oluşturabilirsiniz.
![kod örneği](file:///Users/apple/Desktop/Ekran%20Resmi%202021-09-06%2016.49.17.png)

3._Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım._
```sql
UPDATE author
SET id = '28745',
	  name = 'tuyan ceren',
	  email = 'tuyanceren@icloud.com'
WHERE id = '23';
```
4._Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım._
```sql
DELETE FROM author 
WHERE id = 12;
-- yada WHERE komutundan sonra bunlarıda yazabilirsiniz.
DELETE FROM author 
WHERE name = 'tuyan';
WHERE email = 'example@example.com'
```
-------------
Sorgu senaryolarını [dvdrental.tar](https://www.postgresqltutorial.com/wp-content/uploads/2019/05/dvdrental.zip) isimli dosyayı indirerek gerçekleştirebilirsiniz.
