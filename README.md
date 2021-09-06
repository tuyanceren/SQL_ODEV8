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

**[Mockaroo](https://www.mockaroo.com) ya tıklayarak sizde kendi tablonuzu oluşturabilirsiniz.**
```sql
insert into employee (id, name, email, birthday) values (1, 'Adam', 'acolam0@google.com.hk', '9/16/1944');
insert into employee (id, name, email, birthday) values (2, 'Jordan', 'jelverstone1@marketwatch.com', '9/11/1983');
insert into employee (id, name, email, birthday) values (3, 'Nat', 'nrubert2@deviantart.com', '3/30/1916');
insert into employee (id, name, email, birthday) values (4, 'Roch', 'rwallett3@yolasite.com', '12/31/2011');
insert into employee (id, name, email, birthday) values (5, 'Ewan', 'eorbine4@reverbnation.com', '10/16/1937');
insert into employee (id, name, email, birthday) values (6, 'Alair', 'agreatbatch5@naver.com', '7/3/2011');
insert into employee (id, name, email, birthday) values (7, 'Maure', 'mhallan6@msn.com', '4/24/1973');
insert into employee (id, name, email, birthday) values (8, 'Duff', 'dsazio7@nydailynews.com', '1/10/1902');
insert into employee (id, name, email, birthday) values (9, 'Cyndia', 'clepere8@yolasite.com', '11/15/1985');
insert into employee (id, name, email, birthday) values (10, 'Laryssa', 'ldohmer9@360.cn', '12/17/2001');
insert into employee (id, name, email, birthday) values (11, 'Phillipe', 'pjeffa@hhs.gov', '10/31/1926');
insert into employee (id, name, email, birthday) values (12, 'Maddie', 'mferronb@theguardian.com', '6/22/2020');
insert into employee (id, name, email, birthday) values (13, 'Giffer', 'givensc@google.fr', '8/30/1951');
insert into employee (id, name, email, birthday) values (14, 'Lyndy', 'lbenitod@bluehost.com', '6/18/1957');
insert into employee (id, name, email, birthday) values (15, 'Lanette', 'lkondratoviche@baidu.com', '10/18/2002');
insert into employee (id, name, email, birthday) values (16, 'Danna', 'dailwardf@yellowbook.com', '5/15/1930');
insert into employee (id, name, email, birthday) values (17, 'Francyne', 'fdempseyg@goo.ne.jp', '1/3/1952');
insert into employee (id, name, email, birthday) values (18, 'Gwennie', 'gyeelesh@nationalgeographic.com', '10/6/1997');
insert into employee (id, name, email, birthday) values (19, 'Eolande', 'ewhetsoni@wikispaces.com', '1/15/1996');
insert into employee (id, name, email, birthday) values (20, 'Mavra', 'mhandysidej@addtoany.com', '1/15/2008');
insert into employee (id, name, email, birthday) values (21, 'Delano', 'dheathornk@example.com', '10/2/1936');
insert into employee (id, name, email, birthday) values (22, 'Justine', 'jmarcuml@devhub.com', '1/21/1955');
insert into employee (id, name, email, birthday) values (23, 'Giorgi', 'gbrandsm@dailymail.co.uk', '1/24/1909');
insert into employee (id, name, email, birthday) values (24, 'Ollie', 'odoonen@wunderground.com', '12/10/1945');
insert into employee (id, name, email, birthday) values (25, 'Ferdie', 'fmooreyo@jiathis.com', '7/16/1928');
insert into employee (id, name, email, birthday) values (26, 'Lacee', 'lterbrugp@mapy.cz', '11/23/1979');
insert into employee (id, name, email, birthday) values (27, 'Lammond', 'lmenureq@indiegogo.com', '3/15/1934');
insert into employee (id, name, email, birthday) values (28, 'Amanda', 'afintophr@qq.com', '11/8/1906');
insert into employee (id, name, email, birthday) values (29, 'Val', 'vfinlows@noaa.gov', '4/6/1930');
insert into employee (id, name, email, birthday) values (30, 'Angy', 'aailsburyt@hostgator.com', '2/6/1931');
insert into employee (id, name, email, birthday) values (31, 'Dorelia', 'dcherrisonu@telegraph.co.uk', '8/25/1925');
insert into employee (id, name, email, birthday) values (32, 'Danyelle', 'dallomv@craigslist.org', '5/18/1907');
insert into employee (id, name, email, birthday) values (33, 'Aretha', 'abuschw@ovh.net', '1/19/1986');
insert into employee (id, name, email, birthday) values (34, 'Leopold', 'lmorpheyx@jalbum.net', '2/19/1923');
insert into employee (id, name, email, birthday) values (35, 'Adriena', 'ajosephiy@blog.com', '7/1/1958');
insert into employee (id, name, email, birthday) values (36, 'Wilow', 'wmcwhirterz@xinhuanet.com', '7/18/1933');
insert into employee (id, name, email, birthday) values (37, 'Travus', 'tketchen10@com.com', '1/28/1962');
insert into employee (id, name, email, birthday) values (38, 'Freemon', 'fromaynes11@trellian.com', '10/7/1926');
insert into employee (id, name, email, birthday) values (39, 'Valerye', 'vranderson12@biblegateway.com', '8/24/1945');
insert into employee (id, name, email, birthday) values (40, 'Nollie', 'ntrahearn13@merriam-webster.com', '10/18/1923');
insert into employee (id, name, email, birthday) values (41, 'Wyatan', 'wvansaltsberg14@w3.org', '7/28/1992');
insert into employee (id, name, email, birthday) values (42, 'Pascal', 'pdiffley15@ftc.gov', '8/30/1990');
insert into employee (id, name, email, birthday) values (43, 'Crystie', 'croels16@nydailynews.com', '1/23/1978');
insert into employee (id, name, email, birthday) values (44, 'Barnebas', 'bgurg17@newyorker.com', '8/20/1978');
insert into employee (id, name, email, birthday) values (45, 'Thekla', 'tdomokos18@yellowpages.com', '2/13/1931');
insert into employee (id, name, email, birthday) values (46, 'Shelbi', 'sbrotherhood19@elegantthemes.com', '2/4/1967');
insert into employee (id, name, email, birthday) values (47, 'Aida', 'achansonne1a@admin.ch', '8/8/1935');
insert into employee (id, name, email, birthday) values (48, 'Alejoa', 'aterrington1b@nytimes.com', '12/12/2020');
insert into employee (id, name, email, birthday) values (49, 'Noellyn', 'nnono1c@google.nl', '9/14/2008');
insert into employee (id, name, email, birthday) values (50, 'Madelin', 'mondrusek1d@netvibes.com', '6/12/1965');
```
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
