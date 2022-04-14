# Data Base

### Learning objectives:
* Relational databases
* Keys and unique values
* Planning a database
* Creating tables
* Defining relationships
* Normalization and denormalization
* Writing queries
* Sorting results
* Joining tables
* Modifying data

---

## Introduction

**A database:** is a structure that stores information in an organized, consistent, reliable, and searchable way. 


 Rows are sometimes called records and columns are sometimes called fields

 **Databses:** 
 * provide structure for data.
 * allows us to enforce certain rules on our data too.
 * protect data from unauthorized access or changes.
  
  **a unique value:** is a value that doesn't show up in any other row in a given column.

**A key** is a value we can use to refer to only one specific row or record

**composite key:** two or more fields taken together to act as a unique identifier


**Types of Relationshop:** 
* one - to - many
* many - to - many
* one - to - one


**A transaction:** A transaction is a collection of steps that must all be completed in order for a change to be made to the database.

transaction: -> ACID
* **A  => Atomic** > is indivisible.
* **C => consistent** >  means that whatever the transaction does, it needs to leave the database in a valid or consistent state.
* **I => isolated** > means that while the activities in the transaction are being completed, nothing else can make changes to the data involved.
* **D => durable** > means that the information we change in the transaction actually gets written to the database.
  

**SQL:** Structured Query Language.

#### Relational Database mangement system(RDBMS) tools:

![Relational](https://user-images.githubusercontent.com/70604321/163282288-344889c4-5647-4949-93b8-61f7f8bb5ae8.PNG)


#### SQL:


![Capture](https://user-images.githubusercontent.com/70604321/163282597-3418f2a0-fe06-477e-9c77-d12492e36f8e.PNG)

      * In these roles, SQL acts as a DDL or a data definition language, and a DCL, or a data control language.


**SQL Statement:**
* Clause
* predicate
* Expression


---

# Tables

**entity relationship diagrams or ER diagrams :**
A diagrams that uses tables,fields,and relationship to paln a database.


**UUID, a universally-unique identifier, which is much longer and therefore more difficult for an attacker to guess.**

---
## RelationShip

**One-to-many:**

![Capture](https://user-images.githubusercontent.com/70604321/163290355-62f252b9-60c3-4575-b9f2-1422d540ea98.PNG)


**many-to-many:**

![Capture](https://user-images.githubusercontent.com/70604321/163291401-897b9454-125f-40a3-9e93-a98ce2c1f723.PNG)

**referential integrity:**
the database will be aware of the relationship and will not let you or another user modify data in a way that violates that relationship.

**cascading:**if you delete a record and the database goes on and deletes other records associated with that record.

## DtaBase Optimisation

**normalization rules:**
* first normal form (1NF)
* second normal form (2NF)
* third normal form (3NF)
  

  **first normal form (1NF):**
  values in each cell are atomic, and that tables have no repeating groups.


  **Second normal form:**
  no value in our table should depend only on part of a key that can be used to uniquely identify a row.

  **third normal form (3NF)**
  value shouldn't be stored if the can be calculated from another non-key field.

  **Denormalization** is the process of intentionally duplicating information in tables in violation of normalization rules.


  ---
  **tored procedures** 
  *  It contains a series of commands dtored on database.
  *  avoid having to write out a long or detailed query if it's something you use frequently.
  *  provide safe or approved ways of dealing with sensitive data.

**SQL injection:**
type of attck that includes part of sql command entered as a value to hijack a query and change how it works.

**RDBMS:**
* SQL Server Microsoft
* Oracle
* dBase
* FileMaker Pro
* Microsoft Access
* MySQL
* mariDB
* SAP HANA
* SQLite
  
  DeskTop databses:
  * access
  * FileMaker Pro

Enterprise database:
* SQL Server Microsoft
* Oracle
* SAP HANA

### NOSQL (NOT Only SQL)
* Unstructured data
* key-value pairs
* Graph
* Object
* GEoGraph

  ---
