# E-Commerce Database Schema

## Project Overview
This project is a submission of the Database Management System Assignment.  
The goal is to design and implement a relational database schema for an E-commerce Store using MySQL.  

The schema supports:
- Customer management  
- Product catalog  
- Orders and order details  
- Payments  
- Relationships between entities (One-to-Many, Many-to-Many)


## Database Schema

### Entities & Relationships
1. **Customers** – store customer information  
2. **Products** – catalog of items available for sale  
3. **Orders** – records of customer purchases  
4. **Order_Items** – junction table for products in each order  
5. **Payments** – records of customer payments  

**Relationships:**
- One Customer → Many Orders  
- One Order → Many Order_Items  
- One Product → Many Order_Items  
- One Order → One Payment  


## SQL Schema

The schema is implemented in a single `.sql` file.


## How to Run
1. Install [MySQL](https://dev.mysql.com/downloads/).
2. Open your MySQL client or MySQL Workbench.
3. Run the SQL script provided

   ```bash
   SOURCE db_project.sql;
