# Data Warehouse Persian Date Table
## Summary
Simple the **Gregorian** and **Persian (Shamsi)** date table for using in the ETL process or Data Warehouses. With this date table you can convert dates and create date intensive reports. 
## Setup
1. First you should import or create a base date table into your databases using one of thess steps :
    - Import **date_table_1970_to_2099.csv** file into your database    
    - Execute **date_table.tsql** query file
2. Create View **view_today.tsql** for query today and related to today's dates
## Examples
### View Today Date
```sql
SELECT * FROM [date] where [cc_is_today] = 1
```