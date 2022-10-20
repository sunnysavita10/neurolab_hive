# Neuro lab


![image](https://user-images.githubusercontent.com/115451707/196919992-edcfea8b-e3f6-4f35-9398-43be66b5622d.png)



1. Write hive over the terminal

```
>hive
```
it will redirect to the the hive shell.

2. show the available databases in the hive

```
show databases
```

3. Use the current database in the hive

```
use <database_name>
```

4. Create a new database in the hive

```
create database <database_name>
```

5. describe your database in the hive

```
describe <database_name>
```

6. create a table in hive

```
create table <table_name>
(column_name datatype) 
row format delimited 
fields terminated by ',';
```
8. we can craete one sample table.

```
create table ineuron 
(emp_id int,
 location string, 
 email_id string) 
 row format delimited
 fields terminated by ‘ , ’ ;
)

```

10. describe the table

```
describe formatted ineuron
```
11. check the location of the table.

12. create a .csv file in your system and write data to csv file.

```
101 hyd sunny@ineuron.ai
102 blr sudh@ineuron.ai
103 bpl krish@ineuron.ai
```

13. keep your .csv file in the give table location

14. fetch the data from the table

```
select * from ineuron;
```

9. alter the table in hive

```
alter table table_name to new_table_table;
```


