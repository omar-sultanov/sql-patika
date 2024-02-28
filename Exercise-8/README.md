1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
```
CREATE TABLE employee(
	id integer,
	name VARCHAR(50), 
	birthday DATE, 
	email VARCHAR(100)
)
```

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

```
insert into employee (id, name, email, birthday) values (1, 'Cinderella', 'cderisly0@hhs.gov', '2021-12-05');
insert into employee (id, name, email, birthday) values (2, 'Effie', 'ebyfford1@indiegogo.com', '2000-03-05');
insert into employee (id, name, email, birthday) values (3, 'Boris', 'bosmon2@cbslocal.com', '2012-02-22');
insert into employee (id, name, email, birthday) values (4, 'Lin', 'lpitherick3@stanford.edu', '2020-01-10');
insert into employee (id, name, email, birthday) values (5, 'Lenci', 'lboichat4@taobao.com', '2004-10-30');
insert into employee (id, name, email, birthday) values (6, 'Towny', 'tprall5@scientificamerican.com', '2000-06-01');
insert into employee (id, name, email, birthday) values (7, 'Roberto', 'rlefever6@umich.edu', '2001-04-07');
insert into employee (id, name, email, birthday) values (8, 'Hilarius', 'hdignall7@webmd.com', '2005-12-16');
insert into employee (id, name, email, birthday) values (9, 'Amandy', 'alygoe8@marketwatch.com', '2003-06-24');
insert into employee (id, name, email, birthday) values (10, 'Rem', 'rrussi9@opera.com', '2023-04-01');
insert into employee (id, name, email, birthday) values (11, 'Lorene', 'lcancellora@amazon.co.jp', '2004-01-29');
insert into employee (id, name, email, birthday) values (12, 'Lorena', 'ldorsetb@sciencedirect.com', '2010-11-03');
insert into employee (id, name, email, birthday) values (13, 'Brita', 'bwainmanc@nih.gov', '2024-01-27');
insert into employee (id, name, email, birthday) values (14, 'Maggie', 'mdablingd@salon.com', '2022-02-17');
insert into employee (id, name, email, birthday) values (15, 'Georgie', 'gnevinsone@ask.com', '2003-03-07');
insert into employee (id, name, email, birthday) values (16, 'Kandace', 'kshirerf@reddit.com', '2000-10-28');
insert into employee (id, name, email, birthday) values (17, 'Nye', 'nardyg@mediafire.com', '2003-07-15');
insert into employee (id, name, email, birthday) values (18, 'Mikkel', 'mklimush@pbs.org', '2016-06-03');
insert into employee (id, name, email, birthday) values (19, 'Lelah', 'lromai@smugmug.com', '2005-12-23');
insert into employee (id, name, email, birthday) values (20, 'Bryant', 'bturtonj@google.co.uk', '2009-03-20');
insert into employee (id, name, email, birthday) values (21, 'Jania', 'jsuttlek@gravatar.com', '2000-07-19');
insert into employee (id, name, email, birthday) values (22, 'Winona', 'wdurnfordl@mlb.com', '2021-04-26');
insert into employee (id, name, email, birthday) values (23, 'Ursa', 'umacgilfoylem@csmonitor.com', '2023-07-21');
insert into employee (id, name, email, birthday) values (24, 'Marje', 'mgawthorpn@dot.gov', '2012-12-28');
insert into employee (id, name, email, birthday) values (25, 'Brade', 'bgoghino@hp.com', '2015-12-05');
insert into employee (id, name, email, birthday) values (26, 'Sherilyn', 'shuttenp@google.co.jp', '2001-05-25');
insert into employee (id, name, email, birthday) values (27, 'Madelyn', 'mroebyq@answers.com', '2018-11-11');
insert into employee (id, name, email, birthday) values (28, 'Datha', 'dleithgoer@xing.com', '2019-02-06');
insert into employee (id, name, email, birthday) values (29, 'Trudie', 'tfilsons@unblog.fr', '2017-12-28');
insert into employee (id, name, email, birthday) values (30, 'Guinna', 'ghanhardt@issuu.com', '2013-06-28');
insert into employee (id, name, email, birthday) values (31, 'Nealy', 'nberringeru@howstuffworks.com', '2000-03-02');
insert into employee (id, name, email, birthday) values (32, 'Lind', 'lzamboniniv@mtv.com', '2014-12-09');
insert into employee (id, name, email, birthday) values (33, 'Normy', 'njonkew@techcrunch.com', '2008-09-24');
insert into employee (id, name, email, birthday) values (34, 'Rosie', 'rmagnusx@bluehost.com', '2018-12-24');
insert into employee (id, name, email, birthday) values (35, 'Anastasie', 'abilsfordy@mail.ru', '2013-12-16');
insert into employee (id, name, email, birthday) values (36, 'Kattie', 'kcansdellz@cornell.edu', '2019-03-09');
insert into employee (id, name, email, birthday) values (37, 'Edsel', 'eboyde10@samsung.com', '2008-12-04');
insert into employee (id, name, email, birthday) values (38, 'Hermina', 'hcasserly11@aboutads.info', '2011-12-06');
insert into employee (id, name, email, birthday) values (39, 'Janessa', 'jfane12@google.nl', '2018-08-11');
insert into employee (id, name, email, birthday) values (40, 'Meryl', 'mclementucci13@prnewswire.com', '2006-06-03');
insert into employee (id, name, email, birthday) values (41, 'Noak', 'npowdrell14@latimes.com', '2023-08-21');
insert into employee (id, name, email, birthday) values (42, 'Sandi', 'smatuszkiewicz15@nba.com', '2011-04-07');
insert into employee (id, name, email, birthday) values (43, 'Ben', 'bdavidovics16@squarespace.com', '2011-08-18');
insert into employee (id, name, email, birthday) values (44, 'Ethelyn', 'ekringe17@myspace.com', '2010-05-20');
insert into employee (id, name, email, birthday) values (45, 'Gale', 'gcallister18@rediff.com', '2000-08-18');
insert into employee (id, name, email, birthday) values (46, 'Bondon', 'bgodley19@wordpress.com', '2004-01-31');
insert into employee (id, name, email, birthday) values (47, 'Feliza', 'fshillom1a@bing.com', '2010-07-05');
insert into employee (id, name, email, birthday) values (48, 'Vivien', 'vfaire1b@biblegateway.com', '2012-11-26');
insert into employee (id, name, email, birthday) values (49, 'Vernon', 'vlamminam1c@eepurl.com', '2002-08-18');
insert into employee (id, name, email, birthday) values (50, 'Dame', 'dheugh1d@tinyurl.com', '2022-01-17');

```

3. Sütunların her birine göre diğer sütunları güncelleyecek 3 adet UPDATE işlemi yapalım.

```
update employee
set name = 'update1'
where id>48;

update employee
set email = 'ru-mm@mail.ru'
where name='Marietta';

update employee
set birthday = '2022-10-22'
where id<5;
```

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

```
delete from employee
where email='acristofol1d@barnesandnoble.com'
returning *;

DELETE FROM employee
WHERE name='Dame'
RETURNING *;

DELETE FROM employee
WHERE name LIKE 'N%'
RETURNING *;

DELETE FROM employee
WHERE id>40
RETURNING *;

DELETE FROM employee
WHERE email LIKE '%m%'
RETURNING *;
```