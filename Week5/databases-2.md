# Daily Review (11th Feb)
### Databases 3:
- SQL Joins
- SQL Functions
- Database relationships
- Using SQL with Python

--- 

### In one sentence what is/are:

**SQL Joins**
> "Join clause is used to combine rows from two or more tables based on a relationship between them"

**SQL Functions**
> "Functions built into SQL such as concat, substring, count, current date and averages"

**Database Relationships**
> "How tables are connected in a database, e.g. one-to-one, one-to-many, or many-to-many" 

**Using SQL with Python**
> "How to call SQL queries using python (pymysql)"

---

### What would you tell yourself when using:

**SQL Joins**
- If you want a do a full join you need to combine a union of left and right joins in MYSQL. Some other SQL languages will allow you to do a full join without this.
- Consider the structure of your data before selecting which join you'll use
- Foreign keys aren't necessary for joins but they are good practice moving forward
- Inner joins will only return data that relates to keys that exist in both/all tables


**SQL Functions**
- If want to perform an operation on your data, there is probably a SQL function for that
- 99% of the time you wont need to make your own function, they are inbuilt

**Database Relationships**
- When building a relationship, we can use the primary key from one table and use it as a foreign key in the second table
- Many-to-many relationships we can link the data between the tables.

**Using SQL with Python**
- When making changes always commit them to the DB with a connection
- Close the connection before teminating your app/codebase
- Open and close cursor within the same function