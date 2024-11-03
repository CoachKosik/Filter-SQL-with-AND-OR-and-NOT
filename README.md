# Filter SQL with AND, OR, and NOT

## Objective

This lab aims to enhance the user's ability to construct complex SQL queries using logical operators like `AND`, `OR`, and `NOT`. By mastering these techniques, users can effectively filter and retrieve specific data from databases, enabling them to conduct thorough security investigations and make informed decisions.

## Project description

This project focuses on advanced SQL querying techniques to filter and retrieve specific data from a database. By leveraging `AND`, `OR`, and `NOT` operators, users can combine multiple conditions to accurately target desired information. This skill is essential for security analysts to investigate incidents, identify vulnerabilities, and make informed decisions. 

## Skills Learned

* **Complex Query Construction:** Building SQL queries with multiple conditions using `AND`, `OR`, and `NOT` operators.
* **Data Filtering:** Precisely filtering data based on various criteria to extract relevant information.
* **Data Analysis:** Interpreting query results to identify potential security issues or trends.
* **Database Interaction:** Effectively interacting with a database to retrieve and analyze data.

By mastering these skills, it becomes possible to efficiently extract and analyze data from large datasets, enabling informed decision-making and effective security measures.

## Tools Used

* **SQL Database:** A database management system used to store and manage structured data.
* **SQL Query Language:** Used to interact with the database and retrieve specific information.
* **MariaDB Shell:** A command-line interface for interacting with the MariaDB database.

By utilizing these tools and SQL's logical operators (AND, OR, NOT), users can effectively filter and combine multiple conditions to extract precise information from complex datasets. This is crucial for conducting in-depth security analyses and making informed decisions.

## Steps
1. Retrieve employee device data
* Your team is investigating failed login attempts that were made after business hours. You want to retrieve this information from the login activity. You’ll identify all unsuccessful attempts after 18:00.
  * Use the AND operator to retrieve the failed login attempts that occurred after business hours. Replace the X and Y with the correct values to filter for the records you need:
     * ![an or not 1 ](https://github.com/user-attachments/assets/140a71c0-0e00-4244-8c17-5e3eb1ac765a)
     * ![an or not 2](https://github.com/user-attachments/assets/9a421704-77dc-48f2-9729-57f507ae3d26)
      
2. Retrieve login attempts on specific dates
* Your team is investigating a suspicious event that occurred on '2022-05-09'. You want to retrieve all login attempts that occurred on this day and the day before ('2022-05-08').
  * Use the OR operator to retrieve the failed login attempts on the specified days. Replace the X and Y with the correct values to filter for the records you need:
    * ![an or not 3](https://github.com/user-attachments/assets/35b34397-fd44-44e9-aed2-f2399a9439e8)
    * ![an or not 4](https://github.com/user-attachments/assets/7820ddb0-ab36-4f5b-b38b-fe0b7275c0bd)

3. Retrieve login attempts outside of Mexico
* Now, your team is investigating logins that did not originate in Mexico, and you need to find this information. Note that the country field includes entries with 'MEX' and 'MEXICO'. You should use the NOT and LIKE operators and the matching pattern 'MEX%'.
  * Run the following SQL query to retrieve login attempts that did not originate in Mexico. Replace X with the correct operator and Y with the correct pattern to filter for the information you need:
    * ![an or not 5](https://github.com/user-attachments/assets/bb6926b2-46a6-4ee9-ae3f-b17ea9e17a67)
    * ![an or not 6](https://github.com/user-attachments/assets/a52585bc-8ab1-4e52-8a27-a2ff9b7e7e7b)

4. Retrieve employees in Marketing
* Your team is updating employee machines, and you need to obtain the information about employees in the 'Marketing' department who are located in all offices in the East building (such as 'East-170' or 'East-320').
    * Write a SQL query to retrieve this information from the employees table. Select all columns and include filters on the department and office columns to return only the needed records.
    * ![an or not 7](https://github.com/user-attachments/assets/a3b65f06-53cb-4572-a248-c21523095008)

5. Retrieve employees in Finance or Sales
* Now, your team needs to perform a different update to the computers of all employees in the Finance or the Sales department, and you need to locate information on these employees.
    * Write a SQL query to retrieve records for employees in the 'Finance' or the 'Sales' department.
    * ![an or not 8](https://github.com/user-attachments/assets/a1b89f4f-e526-4b6e-b8d8-20df57eb4b55)

6. Retrieve all employees not in IT
* Your team needs to make one more update. This update was already made to employee computers in the Information Technology department. The team needs information about employees who are not in that department. You should use the NOT operator to identify these employees.
    * Write a SQL query to retrieve records for employees who are not in the 'Information Technology' department.
    * ![an or not 9](https://github.com/user-attachments/assets/94a560e5-2a17-4d6b-a5bb-760961112621)

### Summary

This activity provided hands-on experience in constructing complex SQL queries using logical operators like AND, OR, and NOT. By effectively combining these operators, users can precisely filter and retrieve specific data from databases, enabling thorough analysis and informed decision-making.
