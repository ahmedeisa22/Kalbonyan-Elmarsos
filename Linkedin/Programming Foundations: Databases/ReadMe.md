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
* one - two - many
* many - two - many
* one - two - one


**A transaction:** is a set of operations that must all

transaction: -> ACID
* **A  => Atomic** > is indivisible.
* **C => consistent** >  means that whatever the transaction does, it needs to leave the database in a valid or consistent state.
* **I => isolated** > means that while the activities in the transaction are being completed, nothing else can make changes to the data involved.
* **D => durable** > means that the information we change in the transaction actually gets written to the database.
  

**SQL:** Structured Query Language.
