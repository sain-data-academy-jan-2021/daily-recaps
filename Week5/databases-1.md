# Daily Review (10th Feb)
### Databases:
- Databases
- SQL
- DDL/DML
- Data types

--- 

### In one sentence what is/are:
**Databases**
> "Structured relationship of data"

**SQL**
> "Structured Query Language - used to query to the database"
> "Declarative language - expresses the logic of a computation without describing its control flow"

**DDL/DML**
> "Data Definition Language - syntax for creating or modifying a database object such as tables, indicies and users"
> "Data Manuipulation Language - modifying the data itself"

**Data types (list)**
> VARCHAR or CHAR - Similar to a string in python with a defined limit of characters

> DECIMAL - Similar to a float in python

> INTEGER or INT - Same as python

> BOOL or BOOLEAN - Same as python

> DATETIME - Same as python


---

### What would you tell yourself when using:

**Databases**
- More efficient than using CSV and TXT files

**SQL**
- Declarative, not imparative
- Semi-colon after entering commands
- Ignores whitespace
- You can use auto-increment (important for primary keys)
- Use "Not Null" to ensure a value is entered when inserting data
- Use the "Limit" keyword to limit query responses

**Data types**
- DECIMAL data type requires 2 arguments to specify the units eitherside of the point- default (10,0)
- When using the default parameters for the DECIMAL data type e.g.(10,0), data will be formated as INTEGERS rather than DECIMALS.
    - Change the parameters before importing data
- When using VARCHAR & CHAR if you don't enter an argument you can only input a single character
    - Make sure you enter a numbers
- INTEGER has a max limit of 255 digits
- BOOL or BOOLEAN - Zero is considered false, One is considered true

**Working with tables (SQL hints)**
- CREATE
- DROP
- TRUNCATE
- ALTER


**Working with data (SQL hints)**
- INSERT
- UPDATE
- SELECT
- DELETE