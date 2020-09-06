# Summary of Class 03 Readings

## [Inside A Computer](https://edu.gcfglobal.org/en/computerbasics/inside-a-computer/1/)

### Motherboard I the main circuit board, connecting the different components of the computer together (CPU, memory, graphics card).
### CPU, or processor, carries out the commands of the computer. It is what processes the tasks given to the computer like pressing a key, or opening an application.
### RAM, short for randomly accessible memory, stores short term information that is happening on the computer, like an open word document that has unsaved changes to it. Once the changes are saved they get written to the computers hard drive.
### The hard drive is the computers own persistent storage. When you turn your computer off that information won't be lost.
### Expansion cards. Small pieces of hardware that carry out a specific tasks, like a graphics card or network card.

## [Postgres INSERT](https://www.postgresqltutorial.com/postgresql-insert/)
`INSERT` allows you to add a new row of data to a table. Each column in that row needs to be exaclty how SQL is expecting it, or it won't process the query. You can have the query respond with some of the inserted row by saying `RETURNING *`, replace the * with specific columns to see what data was entered for that column.

## [Postgres SELECT](https://www.postgresqltutorial.com/postgresql-select/)
Using `SELECT` query's asks a SQL table for specific data. You can tell SQL exactly what data you want to be returned. To do this, use very specific key words to say if you want to sort, filter, group depending on what you need. 

## [Postgres UPDATE](https://www.postgresqltutorial.com/postgresql-update/)
The `UPDATE` keyword lets you update a row in a SQL table. It will update the columns you specify for the given row.

## [Postgres DELETE](https://www.postgresqltutorial.com/postgresql-delete/)
Using the `DELETE` keyword lets you delete row(s). It will return the row that was deleted.