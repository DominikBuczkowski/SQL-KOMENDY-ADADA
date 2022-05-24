# NIE MUSI BYĆ Z DUŻEJ | MUSZĄ BYĆ ŚREDNIKI NA KONIEC


 `mysql -u root`       logowanie do sql
 
 `create database "nazwa";`    tworzenie bazy danych
 
 `use "nazwa";`      użycie bazy danych
 
 `create table "nazwa tabeli"(id INT AUTO_INCREMENT PRIMARY KEY, imie VARCHAR(45), nazwisko VARCHAR(45), telefon VARCHAR(13));` tworzenie tabeli
 
 `drop table "nazwa";` usuwanie tabeli
 
 `show tables;` pokazanie tabel
 
 `show columns from "nazwa";` pokazanie struktury kolumny
 
 `insert into "nazwa  values(1, "imie", "nazwisko" "numer");` wprowadzanie danych do tabeli
 
 > wprowadzanie danych po koleji według kolejności wprowadzania wczesniejszej tabeli
 











## ZADANIA

```
create table produkty(id int auto_increment primary key, nazwa varchar(45), jednostka varchar(15),cena float, opis TEXT);
create table zamowienie(id int auto_increment primary key, idProdukt varchar(25), ilosc float, idKlient varchar(10));
create database zamowienie(ID int auto_increment primary key, idklient INT, ilosc FLOAT, idproudkt INT);
insert into omatko  values(1, "twoja", "stara", "2115");
```
