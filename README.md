# bookish-garbanzo
## DBMS Notes 

### Introduction 

- A collection of interrelated data and programs used to access the data.  

- Programs enable creating, modifying records and use of constraints to maintain consistency. 

- DBMSs perform updates within transactions which maintain ACID properties. 

### Transaction ACID Properties  

1. Atomicity: all operations of the transaction are applied in full or rolled back in full and not partially. 

2. Consistency: multiple users modifying the same data at the same time must leave the database in a consistent state when both operations are completed. 

3. Isolation: each transaction is separated from the effects of other concurrent transactions. 

4. Durability: once transactions are committed, changes are permanently saved to the database. 

### Primary Keys 

- Unique identifier for each record. 

- Can be single column, or multiple (composite). 

### Foreign Key 

- A copy of a primary key kept in another table as a means of cross-referencing or implementing a relationship between tables. 

### SQL 

- Declarative language: used to specify what information to get, not the procedure for how to get it. 

- DBMS creates its own execution plan based on the query. 

### Structure Data 

- CREATE TABLE 

- DROP TABLE 

- ALTER TABLE 
    - ADD COLUMN 
    - DROP COLUMN 

### Querying Data 

- SELECT 

### Manipulating Data 

- INSERT 

- UPDATE 

- DELETE 

### Joining 

- INNER JOIN 

- OUTER JOIN 

    - LEFT 

    - RIGHT 

- FULL 

### Grouping 

- GROUP BY 

### PostgreSQL 

- Open-source object relational database management system. 

- Object relational features are arrays (multi-value attributes) and inheritance (parent-child relationships). 

### Commands 

#### psql 

- Start service: sudo service postgres start 

- Open psql: sudo –u postgres psql 

- To change password (inside psql): \password 

 
### Database API 

Psycopg2: https://www.psycopg.org/docs/usage.html 