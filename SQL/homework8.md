# SQL Ödev 8

## 1. Sorunun Cevabı 

![answer8.1](./images/8.1.JPG)

```sql
CREATE TABLE employee(
id INTEGER PRIMARY KEY,
name VARCHAR(50) NOT NULL,
birthday DATE,
email VARCHAR(50)
);

```
## 2. Sorunun Cevabı 

![answer8.2](./images/8.2.JPG)

```sql
insert into employee (id, name, birthday, email) values (1, 'Richie Yakuntzov', '1971/01/11', 'ryakuntzov0@parallels.com');
insert into employee (id, name, birthday, email) values (2, 'Fayina Jankin', '1958/12/20', 'fjankin1@deliciousdays.com');
insert into employee (id, name, birthday, email) values (3, 'Tripp Founds', '1964/10/20', 'tfounds2@smh.com.au');
insert into employee (id, name, birthday, email) values (4, 'Sandor Lerigo', '1991/11/24', 'slerigo3@cornell.edu');
insert into employee (id, name, birthday, email) values (5, 'Chelsie Francklyn', null, null);
insert into employee (id, name, birthday, email) values (6, 'Guenna Dumsday', '1998/02/17', 'gdumsday5@infoseek.co.jp');
insert into employee (id, name, birthday, email) values (7, 'Marissa Bertelet', '1951/05/24', 'mbertelet6@blogspot.com');
insert into employee (id, name, birthday, email) values (8, 'Addia Korneichuk', '1958/03/06', 'akorneichuk7@sogou.com');
insert into employee (id, name, birthday, email) values (9, 'Bethena Joscelin', '1963/05/08', 'bjoscelin8@cyberchimps.com');
insert into employee (id, name, birthday, email) values (10, 'Reynolds Russe', '1953/03/25', 'rrusse9@devhub.com');
insert into employee (id, name, birthday, email) values (11, 'Pearla Boraston', '2002/03/27', 'pborastona@cmu.edu');
insert into employee (id, name, birthday, email) values (12, 'Patrice Facer', '1995/08/03', 'pfacerb@chronoengine.com');
insert into employee (id, name, birthday, email) values (13, 'Goddart Lanham', '1959/09/09', 'glanhamc@dot.gov');
insert into employee (id, name, birthday, email) values (14, 'Corabella Muzzlewhite', '1973/02/19', 'cmuzzlewhited@quantcast.com');
insert into employee (id, name, birthday, email) values (15, 'Finley Spybey', '1980/12/09', 'fspybeye@miitbeian.gov.cn');
insert into employee (id, name, birthday, email) values (16, 'Tracy Vautre', '1998/05/15', 'tvautref@prweb.com');
insert into employee (id, name, birthday, email) values (17, 'Fanny de Clerc', '1965/09/25', 'fdeg@webeden.co.uk');
insert into employee (id, name, birthday, email) values (18, 'Justen Archdeacon', '1965/12/09', 'jarchdeaconh@w3.org');
insert into employee (id, name, birthday, email) values (19, 'Davy Lawther', '1986/04/18', 'dlawtheri@last.fm');
insert into employee (id, name, birthday, email) values (20, 'Clara Amorts', '1980/06/07', 'camortsj@uol.com.br');
insert into employee (id, name, birthday, email) values (21, 'Henryetta Brimmicombe', '1949/04/19', 'hbrimmicombek@wunderground.com');
insert into employee (id, name, birthday, email) values (22, 'Luce Langford', '1945/03/16', 'llangfordl@nyu.edu');
insert into employee (id, name, birthday, email) values (23, 'Delcina O''Scollee', '1954/08/17', 'doscolleem@jiathis.com');
insert into employee (id, name, birthday, email) values (24, 'Hillier Wellings', '1955/05/24', 'hwellingsn@over-blog.com');
insert into employee (id, name, birthday, email) values (25, 'Isak Sloane', '2002/09/30', 'isloaneo@geocities.jp');
insert into employee (id, name, birthday, email) values (26, 'Collie de Juares', '1956/05/19', 'cdep@cpanel.net');
insert into employee (id, name, birthday, email) values (27, 'Kurtis Gleave', '1960/01/25', 'kgleaveq@ft.com');
insert into employee (id, name, birthday, email) values (28, 'Yettie Barmadier', '1999/09/10', 'ybarmadierr@friendfeed.com');
insert into employee (id, name, birthday, email) values (29, 'Wandie Soff', '1956/11/30', null);
insert into employee (id, name, birthday, email) values (30, 'Zolly Goodman', '1957/06/14', 'zgoodmant@slashdot.org');
insert into employee (id, name, birthday, email) values (31, 'Adria McIlvoray', '1983/08/09', 'amcilvorayu@marriott.com');
insert into employee (id, name, birthday, email) values (32, 'Abby Goulston', '1978/10/18', 'agoulstonv@unicef.org');
insert into employee (id, name, birthday, email) values (33, 'Joe Butte', '1977/09/16', 'jbuttew@youtube.com');
insert into employee (id, name, birthday, email) values (34, 'Demetre Shaefer', '2002/04/18', 'dshaeferx@photobucket.com');
insert into employee (id, name, birthday, email) values (35, 'Aristotle Hairsine', '1955/08/31', null);
insert into employee (id, name, birthday, email) values (36, 'Boote Kuban', '1983/10/27', 'bkubanz@biblegateway.com');
insert into employee (id, name, birthday, email) values (37, 'Tomasine Tampion', '1952/04/18', 'ttampion10@wix.com');
insert into employee (id, name, birthday, email) values (38, 'Ardine Inde', '1954/05/26', 'ainde11@google.com.br');
insert into employee (id, name, birthday, email) values (39, 'Lisetta Scay', '1948/04/13', 'lscay12@wikimedia.org');
insert into employee (id, name, birthday, email) values (40, 'Kirsten Gobourn', '2001/04/29', 'kgobourn13@w3.org');
insert into employee (id, name, birthday, email) values (41, 'Wald Paliser', '1998/07/14', 'wpaliser14@bandcamp.com');
insert into employee (id, name, birthday, email) values (42, 'Stillmann Pearman', '1960/12/15', 'spearman15@bandcamp.com');
insert into employee (id, name, birthday, email) values (43, 'Danica Pennazzi', '1965/09/29', 'dpennazzi16@google.com');
insert into employee (id, name, birthday, email) values (44, 'Mylo Liepmann', '1990/02/02', 'mliepmann17@eepurl.com');
insert into employee (id, name, birthday, email) values (45, 'Cornie Patrickson', '1960/10/16', null);
insert into employee (id, name, birthday, email) values (46, 'Walton Claricoates', '1940/11/10', 'wclaricoates19@seesaa.net');
insert into employee (id, name, birthday, email) values (47, 'Cynthea Shimwell', '1976/07/10', null);
insert into employee (id, name, birthday, email) values (48, 'Joyce Gurden', '1966/11/14', 'jgurden1b@stanford.edu');
insert into employee (id, name, birthday, email) values (49, 'Duffy Dmych', '1951/10/05', 'ddmych1c@constantcontact.com');
insert into employee (id, name, birthday, email) values (50, 'Henka Khosa', '1975/05/18', 'hkhosa1d@cnet.com');

```

## 3. Sorunun Cevabı 

![answer8.3](./images/8.3.JPG)

```sql
UPDATE employee
SET name = 'Ahmet Yıldırım',
	birthday = '1990-02-01',
	email = 'ahmet@gmail.com'
WHERE id = 2 OR name = 'Addia Korneichuk' 
OR birthday = '1973-02-19' OR email = 'hwellingsn@over-blog.com';

```

## 4. Sorunun Cevabı 

![answer8.4](./images/8.4.JPG)

```sql
DELETE FROM employee
WHERE id = 2 OR name = 'Marissa Bertelet' 
OR birthday = '1963-05-08' OR email = 'ryakuntzov0@parallels.com';


```