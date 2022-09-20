mysql> create database sse;
Query OK, 1 row affected (0.13 sec)

mysql> use sse;
Database changed
mysql> CREATE TABLE student(RegNo int(3), Name varchar(15), Gender char(1), DOB int(10), MobileNo int(10), City char(10));
Query OK, 0 rows affected, 3 warnings (0.42 sec)

mysql> desc student;
+----------+-------------+------+-----+---------+-------+
| Field    | Type        | Null | Key | Default | Extra |
+----------+-------------+------+-----+---------+-------+
| RegNo    | int         | YES  |     | NULL    |       |
| Name     | varchar(15) | YES  |     | NULL    |       |
| Gender   | char(1)     | YES  |     | NULL    |       |
| DOB      | int         | YES  |     | NULL    |       |
| MobileNo | int         | YES  |     | NULL    |       |
| City     | char(10)    | YES  |     | NULL    |       |
+----------+-------------+------+-----+---------+-------+
6 rows in set (0.19 sec)

mysql> use sse;
Database changed
mysql> CREATE TABLE faculty(FacNo varchar(4),FacName char(15), Gender char(1), DOB int(10),DOJ int(10),MobileNo int(10));
Query OK, 0 rows affected, 3 warnings (0.20 sec)

mysql> desc faculty;
+----------+------------+------+-----+---------+-------+
| Field    | Type       | Null | Key | Default | Extra |
+----------+------------+------+-----+---------+-------+
| FacNo    | varchar(4) | YES  |     | NULL    |       |
| FacName  | char(15)   | YES  |     | NULL    |       |
| Gender   | char(1)    | YES  |     | NULL    |       |
| DOB      | int        | YES  |     | NULL    |       |
| DOJ      | int        | YES  |     | NULL    |       |
| MobileNo | int        | YES  |     | NULL    |       |
+----------+------------+------+-----+---------+-------+
6 rows in set (0.00 sec)

mysql> CREATE TABLE department(DeptNo varchar(4),DeptName varchar(15),Depthead varchar(4));
Query OK, 0 rows affected (7.93 sec)

mysql> desc department;
+----------+-------------+------+-----+---------+-------+
| Field    | Type        | Null | Key | Default | Extra |
+----------+-------------+------+-----+---------+-------+
| DeptNo   | varchar(4)  | YES  |     | NULL    |       |
| DeptName | varchar(15) | YES  |     | NULL    |       |
| Depthead | varchar(4)  | YES  |     | NULL    |       |
+----------+-------------+------+-----+---------+-------+
3 rows in set (0.00 sec)

mysql> CREATE TABLE course(courseNo varchar(3),coursedesc varchar(14), coursetype char(1), Semno char(1),Hallno varchar(4),Facno varchar(4));
Query OK, 0 rows affected (0.31 sec)

mysql> desc course;
+------------+-------------+------+-----+---------+-------+
| Field      | Type        | Null | Key | Default | Extra |
+------------+-------------+------+-----+---------+-------+
| courseNo   | varchar(3)  | YES  |     | NULL    |       |
| coursedesc | varchar(14) | YES  |     | NULL    |       |
| coursetype | char(1)     | YES  |     | NULL    |       |
| Semno      | char(1)     | YES  |     | NULL    |       |
| Hallno     | varchar(4)  | YES  |     | NULL    |       |
| Facno      | varchar(4)  | YES  |     | NULL    |       |
+------------+-------------+------+-----+---------+-------+
6 rows in set (0.00 sec)

mysql> ALTER TABLE faculty ADD Deptno varchar(4);
Query OK, 0 rows affected (0.34 sec)
Records: 0  Duplicates: 0  Warnings: 0

mysql> desc faculty;
+----------+------------+------+-----+---------+-------+
| Field    | Type       | Null | Key | Default | Extra |
+----------+------------+------+-----+---------+-------+
| FacNo    | varchar(4) | YES  |     | NULL    |       |
| FacName  | char(15)   | YES  |     | NULL    |       |
| Gender   | char(1)    | YES  |     | NULL    |       |
| DOB      | int        | YES  |     | NULL    |       |
| DOJ      | int        | YES  |     | NULL    |       |
| MobileNo | int        | YES  |     | NULL    |       |
| Deptno   | varchar(4) | YES  |     | NULL    |       |
+----------+------------+------+-----+---------+-------+
7 rows in set (0.00 sec)
