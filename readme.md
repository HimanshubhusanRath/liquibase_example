# Liquibase:
* Liquibase is just like a version control tool for Database.
* It keeps track of database changes by using the below two tables.
  * DATBASECHANGELOG : Keeps track of the changes executed on the database.
  * DATABASECHANGELOGLOCK : Maintains a locking mechanism to ensure changes are executed one after the other.  