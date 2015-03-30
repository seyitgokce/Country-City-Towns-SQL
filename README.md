# Country-City-Towns-SQL


Hello. My name is Seyit. 


There are 3 sql files.

city.sql 		->	Cities database
towns.sql 		->	Towns database
country.sql 	->	Countries database


Description for city.sql


Create your database table with this code.

CREATE TABLE IF NOT EXISTS `city` (
  `id` int(11) DEFAULT NULL,
  `ulke_id` int(11) DEFAULT NULL,
  `ad` varchar(50) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8;


Example
INSERT INTO city (id, ulke_id, ad) VALUES (1, 1, 'Adana')



Description for country.sql

Create your database table with this code.

CREATE TABLE IF NOT EXISTS `country` (
  `id` int(11) DEFAULT NULL,
  `ad` varchar(50) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8;


Example
INSERT INTO country (id, ad) VALUES (1, 'Türkiye')


Description for towns.sql

Create your database table with this code.


CREATE TABLE IF NOT EXISTS `towns` (
  `id` int(11) DEFAULT NULL,
  `ulke_id` int(11) DEFAULT NULL,
  `il_id` int(11) DEFAULT NULL,
  `ad` varchar(50) DEFAULT NULL
) ENGINE=InnoDB DEFAULT CHARSET=utf8;


Example
INSERT INTO towns (id, ulke_id, il_id, ad ) VALUES (1, 1, 1, 'Seyhan')
