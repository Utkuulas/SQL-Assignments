# CREATE & UPDATE TABLE
On this chapter, we'll create a ***test*** database includes the ***employee*** table only and update it.

- Firstly, create a new database named ***"test"***
```sql
CREATE DATABASE test;
```

- Create a new table having that properties after
```sql
CREATE TABLE IF NOT EXISTS employee (
	id int,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);
```

- And insert that data
```sql
insert into employee (name, birthday, email) values ('Cynthie Garahan', '2015-11-20', 'cgarahan0@weather.com');
insert into employee (name, birthday, email) values ('Kahlil Hellwig', '2012-06-21', 'khellwig1@fc2.com');
insert into employee (name, birthday, email) values ('Normand Walwood', '2012-04-07', 'nwalwood2@springer.com');
insert into employee (name, birthday, email) values ('Tess Danett', '2021-06-25', 'tdanett3@creativecommons.org');
insert into employee (name, birthday, email) values ('Gillan Haggerston', '2011-02-26', 'ghaggerston4@msu.edu');
insert into employee (name, birthday, email) values ('Arty Nichol', '2011-10-12', 'anichol5@4shared.com');
insert into employee (name, birthday, email) values ('Gussy Bockings', '2021-03-21', 'gbockings6@uol.com.br');
insert into employee (name, birthday, email) values ('Dorita Raveau', '2018-09-27', 'draveau7@weather.com');
insert into employee (name, birthday, email) values ('Bertrand Youle', '2022-09-04', 'byoule8@senate.gov');
insert into employee (name, birthday, email) values ('Anson Nerger', '2022-12-08', 'anerger9@dropbox.com');
insert into employee (name, birthday, email) values ('Quill Vineall', '2020-10-05', 'qvinealla@creativecommons.org');
insert into employee (name, birthday, email) values ('Clarey Callear', '2005-07-07', 'ccallearb@si.edu');
insert into employee (name, birthday, email) values ('Thurston Chucks', '2022-04-17', 'tchucksc@imdb.com');
insert into employee (name, birthday, email) values ('Weber Rouf', '2021-08-31', 'wroufd@npr.org');
insert into employee (name, birthday, email) values ('Leia Rivaland', '2022-01-24', 'lrivalande@fc2.com');
insert into employee (name, birthday, email) values ('Bendite Records', '2022-08-22', 'brecordsf@acquirethisname.com');
insert into employee (name, birthday, email) values ('Amie Templman', '2018-06-02', 'atemplmang@vistaprint.com');
insert into employee (name, birthday, email) values ('Calli Sherrell', '2018-11-28', 'csherrellh@sbwire.com');
insert into employee (name, birthday, email) values ('Dal Bradbury', '2020-01-12', 'dbradburyi@dell.com');
insert into employee (name, birthday, email) values ('Rawley Purches', '2008-09-05', 'rpurchesj@trellian.com');
insert into employee (name, birthday, email) values ('Cesaro Clissold', '2007-05-20', 'cclissoldk@cornell.edu');
insert into employee (name, birthday, email) values ('Dick Fidele', '2001-05-01', 'dfidelel@loc.gov');
insert into employee (name, birthday, email) values ('Torre Mendonca', '2020-05-06', 'tmendoncam@github.com');
insert into employee (name, birthday, email) values ('Terence Harbour', '2001-03-20', 'tharbourn@youtu.be');
insert into employee (name, birthday, email) values ('Rufe Winwright', '2009-07-27', 'rwinwrighto@creativecommons.org');
insert into employee (name, birthday, email) values ('Leonid Scullard', '2014-12-23', 'lscullardp@ow.ly');
insert into employee (name, birthday, email) values ('Minnaminnie Croy', '2012-08-09', 'mcroyq@statcounter.com');
insert into employee (name, birthday, email) values ('Anatollo Scoon', '2000-11-13', 'ascoonr@msn.com');
insert into employee (name, birthday, email) values ('Cahra Brech', '2004-07-10', 'cbrechs@ifeng.com');
insert into employee (name, birthday, email) values ('Oriana Allright', '2001-12-31', 'oallrightt@si.edu');
insert into employee (name, birthday, email) values ('Ulrich Andress', '2001-04-04', 'uandressu@mozilla.com');
insert into employee (name, birthday, email) values ('Dorey Maclean', '2008-07-15', 'dmacleanv@ning.com');
insert into employee (name, birthday, email) values ('Wilden Guilfoyle', '2013-09-02', 'wguilfoylew@yellowpages.com');
insert into employee (name, birthday, email) values ('Georges Lamas', '2015-11-11', 'glamasx@163.com');
insert into employee (name, birthday, email) values ('Anallese MacGragh', '2014-10-10', 'amacgraghy@mozilla.org');
insert into employee (name, birthday, email) values ('Yancy Bernaldo', '2002-02-16', 'ybernaldoz@webeden.co.uk');
insert into employee (name, birthday, email) values ('Nichol Chichgar', '2013-11-23', 'nchichgar10@cnet.com');
insert into employee (name, birthday, email) values ('Anne-marie Paur', '2019-06-11', 'apaur11@domainmarket.com');
insert into employee (name, birthday, email) values ('Louisa Bitterton', '2013-05-28', 'lbitterton12@ehow.com');
insert into employee (name, birthday, email) values ('Heidi Dutnell', '2016-11-22', 'hdutnell13@liveinternet.ru');
insert into employee (name, birthday, email) values ('Eirena MacCoveney', '2022-03-01', 'emaccoveney14@hhs.gov');
insert into employee (name, birthday, email) values ('Elwira Flukes', '2009-11-02', 'eflukes15@boston.com');
insert into employee (name, birthday, email) values ('Zachariah Nisuis', '2011-03-06', 'znisuis16@bravesites.com');
insert into employee (name, birthday, email) values ('Weston Mounsey', '2022-02-10', 'wmounsey17@amazonaws.com');
insert into employee (name, birthday, email) values ('Jerry Salerno', '2007-06-12', 'jsalerno18@ox.ac.uk');
insert into employee (name, birthday, email) values ('Dode Jorry', '2019-02-02', 'djorry19@opera.com');
insert into employee (name, birthday, email) values ('Melany Jozsa', '2014-01-09', 'mjozsa1a@usatoday.com');
insert into employee (name, birthday, email) values ('Johannes Jouannot', '2014-11-15', 'jjouannot1b@nytimes.com');
insert into employee (name, birthday, email) values ('Lari Crosio', '2019-01-03', 'lcrosio1c@blogtalkradio.com');
insert into employee (name, birthday, email) values ('Jenni McElrath', '2011-07-14', 'jmcelrath1d@forbes.com');
insert into employee (name, birthday, email) values ('Ikey Forge', '2016-11-06', 'iforge1e@dropbox.com');
insert into employee (name, birthday, email) values ('Hercule Scraggs', '2012-08-20', 'hscraggs1f@multiply.com');
insert into employee (name, birthday, email) values ('Gregory Dowdam', '2011-09-10', 'gdowdam1g@multiply.com');
insert into employee (name, birthday, email) values ('Dwayne Gliddon', '2018-11-07', 'dgliddon1h@cnet.com');
insert into employee (name, birthday, email) values ('Lyn Brok', '2007-09-01', 'lbrok1i@economist.com');
insert into employee (name, birthday, email) values ('Erich Flaverty', '2002-02-15', 'eflaverty1j@unblog.fr');
insert into employee (name, birthday, email) values ('Jeralee Hulett', '2002-09-05', 'jhulett1k@youku.com');
insert into employee (name, birthday, email) values ('Roseann Fulun', '2017-09-12', 'rfulun1l@nasa.gov');
insert into employee (name, birthday, email) values ('Nanette Frowd', '2007-01-18', 'nfrowd1m@examiner.com');
insert into employee (name, birthday, email) values ('Sadye Brede', '2011-01-03', 'sbrede1n@baidu.com');
insert into employee (name, birthday, email) values ('Kamila Demongeot', '2006-09-06', 'kdemongeot1o@toplist.cz');
insert into employee (name, birthday, email) values ('Mauricio Burgott', '2022-03-14', 'mburgott1p@digg.com');
insert into employee (name, birthday, email) values ('Theda Libbis', '2008-08-08', 'tlibbis1q@chicagotribune.com');
insert into employee (name, birthday, email) values ('Isobel Jans', '2005-07-29', 'ijans1r@cbslocal.com');
insert into employee (name, birthday, email) values ('Menard Siggin', '2022-01-13', 'msiggin1s@uol.com.br');
insert into employee (name, birthday, email) values ('Roby De Beauchemp', '2009-02-25', 'rde1t@ning.com');
insert into employee (name, birthday, email) values ('Margret Ellams', '2012-11-27', 'mellams1u@zdnet.com');
insert into employee (name, birthday, email) values ('Edie Lyddiard', '2007-09-20', 'elyddiard1v@etsy.com');
insert into employee (name, birthday, email) values ('Free Ridel', '2005-08-22', 'fridel1w@prlog.org');
insert into employee (name, birthday, email) values ('Hortensia Ingyon', '2018-02-20', 'hingyon1x@behance.net');
insert into employee (name, birthday, email) values ('Malinda Paxeford', '2014-05-19', 'mpaxeford1y@webeden.co.uk');
insert into employee (name, birthday, email) values ('Karine Hayhurst', '2012-09-15', 'khayhurst1z@artisteer.com');
insert into employee (name, birthday, email) values ('Otes Hyndman', '2016-06-06', 'ohyndman20@joomla.org');
insert into employee (name, birthday, email) values ('Emilio Brouard', '2020-09-25', 'ebrouard21@google.com.au');
insert into employee (name, birthday, email) values ('Koressa McCaffery', '2005-09-22', 'kmccaffery22@feedburner.com');
insert into employee (name, birthday, email) values ('Bartlet Pottberry', '2008-06-17', 'bpottberry23@networkadvertising.org');
insert into employee (name, birthday, email) values ('Nobe Custard', '2022-05-09', 'ncustard24@com.com');
insert into employee (name, birthday, email) values ('Sansone Glasper', '2014-07-02', 'sglasper25@paypal.com');
insert into employee (name, birthday, email) values ('Alla Custard', '2006-02-04', 'acustard26@adobe.com');
insert into employee (name, birthday, email) values ('Ariel Christiensen', '2008-06-21', 'achristiensen27@paginegialle.it');
insert into employee (name, birthday, email) values ('Horatius Geleman', '2020-06-27', 'hgeleman28@uiuc.edu');
insert into employee (name, birthday, email) values ('Christophorus Segges', '2000-11-06', 'csegges29@mtv.com');
insert into employee (name, birthday, email) values ('Alessandro Clifton', '2006-08-27', 'aclifton2a@printfriendly.com');
insert into employee (name, birthday, email) values ('Theodosia Bushaway', '2006-03-22', 'tbushaway2b@yahoo.com');
insert into employee (name, birthday, email) values ('Ulric Kilgannon', '2017-01-27', 'ukilgannon2c@comsenz.com');
insert into employee (name, birthday, email) values ('Devi Goodfellowe', '2002-10-28', 'dgoodfellowe2d@sohu.com');
insert into employee (name, birthday, email) values ('Benedick Normabell', '2007-11-05', 'bnormabell2e@cafepress.com');
insert into employee (name, birthday, email) values ('Bidget Briggdale', '2010-12-04', 'bbriggdale2f@harvard.edu');
insert into employee (name, birthday, email) values ('Sibley Saffer', '2009-03-23', 'ssaffer2g@github.com');
insert into employee (name, birthday, email) values ('Frankie Lewson', '2017-11-21', 'flewson2h@wikipedia.org');
insert into employee (name, birthday, email) values ('Jacinda McIlherran', '2016-10-09', 'jmcilherran2i@com.com');
insert into employee (name, birthday, email) values ('Trixi Brydone', '2021-09-23', 'tbrydone2j@statcounter.com');
insert into employee (name, birthday, email) values ('Roxi Drugan', '2007-12-01', 'rdrugan2k@nature.com');
insert into employee (name, birthday, email) values ('Ives Delf', '2013-09-04', 'idelf2l@blogs.com');
insert into employee (name, birthday, email) values ('Neala Ivchenko', '2011-10-15', 'nivchenko2m@barnesandnoble.com');
insert into employee (name, birthday, email) values ('Pearle Strick', '2018-09-20', 'pstrick2n@dyndns.org');
insert into employee (name, birthday, email) values ('Sylas Jelliman', '2021-10-02', 'sjelliman2o@auda.org.au');
insert into employee (name, birthday, email) values ('Caril Leavey', '2018-12-10', 'cleavey2p@typepad.com');
insert into employee (name, birthday, email) values ('Ferris Beeton', '2009-02-20', 'fbeeton2q@loc.gov');
insert into employee (name, birthday, email) values ('Grantham Frogley', '2022-02-26', 'gfrogley2r@tripod.com');
```

## UPDATE

1. Update emails for names starting with "F" to "UNKNOWN@UNKNOWN" and show the effected rows.
```sql
UPDATE employee
SET email = 'UNKNOWN@UNKNOWN'
WHERE name LIKE 'F%'
RETURNING *;
```
![1](assets/1.png)

2. Change the name of the employee with id = 5 to "James" and show the effected rows.
```sql
UPDATE employee
SET name = CONCAT('James', ' ', RIGHT(name, LENGTH(name) - POSITION(' ' in name)))
WHERE id = 5
RETURNING *;
```
![2](assets/2.png)

3. Decrease the birth year by 5 for those whose name ends with "o" and show the effected rows.
```sql
UPDATE employee
SET birthday = birthday - INTEGER '1825'
WHERE name LIKE '%o'
RETURNING *;
```
![3](assets/3.png)

4. For those whose name starts with S, increase the year of birth by 5 if the age is greater than 10 and show the effected rows.
```sql
UPDATE employee
SET birthday = birthday + INTEGER '1825'
WHERE name LIKE 'S%' AND EXTRACT(YEAR FROM AGE(CURRENT_DATE, birthday)) > 10
RETURNING *;
```
![4](assets/4.png)

5. Add "YOUNG" to the end of the name of those younger than 25, over 18 and show the effected rows.
```sql
UPDATE employee
SET name = CONCAT(name, ' ', 'YOUNG')
WHERE EXTRACT(YEAR FROM AGE(CURRENT_DATE, birthday)) > 18
AND EXTRACT(YEAR FROM AGE(CURRENT_DATE, birthday)) < 25
RETURNING *;
```
![5](assets/5.png)

## DELETE

1. Delete those with the last name "Youle" and show the deleted rows.
```sql
DELETE FROM employee 
WHERE name LIKE '% Youle'
RETURNING *;
```
![6](assets/6.png)

2. Delete the youngest and show the deleted row.
```sql
DELETE FROM employee
WHERE birthday IN (
	SELECT birthday FROM employee
	ORDER BY birthday DESC
	LIMIT 1
)
RETURNING *;
```
![7](assets/7.png)

3. Delete second oldest person and show the deleted row.
```sql
DELETE FROM employee
WHERE birthday IN (
	SELECT birthday FROM employee
	ORDER BY birthday
	LIMIT 1
	OFFSET 1
)
RETURNING *;
```
![8](assets/8.png)

4. Delete names with a "X" in the name and show the deleted rows.
```sql
DELETE FROM employee
WHERE name ILIKE 'X%'
OR name ILIKE '%X%'
OR name ILIKE '%X'
RETURNING *;
```
![9](assets/9.png)

5. Delete those under 6 years old and show the deleted rows.
```sql
DELETE FROM employee
WHERE EXTRACT(YEAR FROM AGE(CURRENT_DATE, birthday)) < 6
RETURNING *;
```
![10](assets/10.png)


