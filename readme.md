# SQL Database Project 


### Complete the following steps to complete the project: 


[![123.png](https://i.postimg.cc/wvNyv8fw/123.png)](https://postimg.cc/G8ch7N1D)

###  1️⃣ Create the above database as shown in the image with the following steps : 
1. Create database named " store ".
2. Create table countries. 
3. Create table users. 
3. Create table orders.
4. Create table order_products. 
5. Create table products. 
  

###  2️⃣ Connect tables using foreign keys when applicable

###  3️⃣ Add the following constraints to each tables

1. **countries**
    1. Add unique constraint to column " name ".
    2. Add not null constraint to column " continent_name ".
  
2. **users**
    1. Add unique constraint to column " email ".
    2. Add check constraint to column " gender " between 'm' or 'f'.

3. **orders**
    1. Add check constraint to column " status " between 'start' or 'finish'.

4. **order_items**
    1. Add default value to column " quantity " value 0.

5. **products**
    1. Add default value to column " price " value 0.
    2. Add not null constraint to column " name ".
    3. Add check constraint to column " status " between 'valid' or 'expired'.


**Bouns : Add default datetime to created_at column which take the timestap when the row is created**

### 4️⃣ Write the DML commands for the following instructions ( choose data randomly ) :
1. Add new row to the countries table.
2. Add new row to the users table.
3. Add new row to the orders table.
4. Add new row to the products table.
5. Add new row to the order_products table.
 
6. Update row from countries table.
7. Delete row from products table.

## Submission ✅:
1. Create new Github repository .  
2. Create new file in the repositry.
3. In the file write all the commands ( DML & DDL ) which you used to complete the above tasks.
4. Commit the new file.
5. Send your repo's link to your "مشرف"


## Grading 🎓:

| # | Criteria | Percentage %
| :---: | :---: |  :---: |
| 1 | <name> Create tables and database as required | 20
| 2 | <name> Connect tables as required | 20
| 3 | <name> Add constraints to the tables column as required | 20
| 4 | <name> Execute all the DML commands  | 20
|  | Total  | 100
  
  
  
