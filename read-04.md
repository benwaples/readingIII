# Summary of Reading for Class-04

## [Joins](https://www.postgresqltutorial.com/postgresql-joins/)
`JOINS` used in SQL combine columns from separate tables into one column bringing along other relevant information with them. A primary key is usually used for the first table, and foreign key for the second table.
### Different types of joins
![diagram of joins](https://sp.postgresqltutorial.com/wp-content/uploads/2018/12/PostgreSQL-Joins.png)

## one-to-one data model - wiki it
thing of two tables, one for dogs and another for dogs brains. Each dog only has one brain and each brain only has one dog. 

## one-to-many data model - again wiki it
think of another 2 tables, one for students and another for submitted homework assignments. Each submitted homework assignment came from one kid, but each kid has submitted many homework assignment.

## many-to-many data model
Two more tables, one for research papers and another for scientists. Each scientist has submitted many papers, and each paper can be finished by many scientist.