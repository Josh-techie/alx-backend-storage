<p align="center">
<img src ="https://th.bing.com/th/id/R.9f535cc8ad4b5d16704435f441b85d86?rik=FqMsiJjQP5TY5A&pid=ImgRaw&r=0">
</p>

---

# MySQL Advanced:

- This project, titled `0x00. MySQL advanced`, is designed to enhance your proficiency in MySQL, focusing on advanced concepts and practical applications. Throughout the project, you will delve into various aspects of MySQL, such as creating tables with constraints, optimizing queries using indexes, implementing stored procedures, functions, views, and triggers in MySQL.

---

## Resources:

To successfully navigate through this project, refer to the following resources:

- [MySQL cheatsheet](https://devhints.io/mysql)
- [MySQL Performance: How To Leverage MySQL Database Indexing](https://www.liquidweb.com/kb/mysql-optimization-how-to-leverage-mysql-database-indexing/)
- [Stored Procedure](https://www.w3resource.com/mysql/mysql-procedure.php)
- [Triggers](https://www.w3resource.com/mysql/mysql-triggers.php)
- [Views](https://www.w3resource.com/mysql/mysql-views.php)
- [Functions and Operators](https://dev.mysql.com/doc/refman/5.7/en/functions.html)
- [Trigger Syntax and Examples](https://dev.mysql.com/doc/refman/5.7/en/trigger-syntax.html)
- [CREATE TABLE Statement](https://dev.mysql.com/doc/refman/5.7/en/create-table.html)
- [CREATE PROCEDURE and CREATE FUNCTION Statements](https://dev.mysql.com/doc/refman/5.7/en/create-procedure.html)
- [CREATE INDEX Statement](https://dev.mysql.com/doc/refman/5.7/en/create-index.html)
- [CREATE VIEW Statement](https://dev.mysql.com/doc/refman/5.7/en/create-view.html)

---

## Learning Objectives:

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
General

- How to create tables with constraints
- How to optimize queries by adding indexes
- What is and how to implement stored procedures and functions in MySQL
- What is and how to implement views in MySQL
- What is and how to implement triggers in MySQL

---

## Tasks:
0. We are all unique!
- **Task:** Write a SQL script that creates a table "users" with specific attributes and constraints.
- **File:** [0-uniq_users.sql](./alx-backend-storage/0x00-MySQL_Advanced/0-uniq_users.sql)

1. In and not out
- **Task:** Write a SQL script that creates a table "users" with additional country attribute and constraints.
- **File:** [1-country_users.sql](./alx-backend-storage/0x00-MySQL_Advanced/1-country_users.sql)

2. Best band ever!
- **Task:** Write a SQL script that ranks country origins of bands based on the number of fans.
- **File:** [2-fans.sql](./alx-backend-storage/0x00-MySQL_Advanced/2-fans.sql)

3. Old school band
- **Task:** Write a SQL script that lists bands with "Glam rock" as their main style, ranked by their longevity.
- **File:** [3-glam_rock.sql](./alx-backend-storage/0x00-MySQL_Advanced/3-glam_rock.sql)

4. Buy buy buy
- **Task:** Write a SQL script that creates a trigger decreasing the quantity of an item after adding a new order.
- **File:** [4-store.sql](./alx-backend-storage/0x00-MySQL_Advanced/4-store.sql)

5. Email validation to sent
- **Task:** Write a SQL script that creates a trigger resetting the attribute "valid_email" only when the email has been changed.
- **File:** [5-valid_email.sql](./alx-backend-storage/0x00-MySQL_Advanced/5-valid_email.sql)

6. Add bonus
- **Task:** Write a SQL script that creates a stored procedure "AddBonus" for adding a new correction for a student.
- **File:** [6-bonus.sql](./alx-backend-storage/0x00-MySQL_Advanced/6-bonus.sql)

7. Average score
- **Task:** Write a SQL script that creates a stored procedure "ComputeAverageScoreForUser" for computing and storing the average score for a student.
- **File:** [7-average_score.sql](./alx-backend-storage/0x00-MySQL_Advanced/7-average_score.sql)

8. Average weighted score
- **Task:** Write a SQL script that creates a stored function "ComputeAverageWeightedScoreForUser" for computing and returning the average weighted score for a student.
- **File:** [8-weighted_average.sql](./alx-backend-storage/0x00-MySQL_Advanced/8-weighted_average.sql)

9. Trigger for average
- **Task:** Write a SQL script that creates a trigger updating the average score of a user when a new correction is added.
- **File:** [9-trigger.sql](./alx-backend-storage/0x00-MySQL_Advanced/9-trigger.sql)

### Advanced Tasks:

10.  Log stats
- **Task:** Write a SQL script that creates a stored procedure "LogStats" for printing statistics about Nginx request logs and top 10 HTTP IPs stored in MySQL.
- **File:** [10-log_stats.sql](./alx-backend-storage/0x00-MySQL_Advanced/10-log_stats.sql)

11. Trigger that prevents deletion
- **Task:** Write a SQL script that creates a trigger preventing the deletion of a user.
- **File:** [11-prevent_delete.sql](./alx-backend-storage/0x00-MySQL_Advanced/11-prevent_delete.sql)

12. Trigger that resets attribute
- **Task:** Write a SQL script that creates a trigger resetting the "average_score" attribute to 0 when a user is deleted.
- **File:** [12-reset_attribute.sql](./alx-backend-storage/0x00-MySQL_Advanced/12-reset_attribute.sql)

13. Factorize
- **Task:** Write a SQL script that creates a stored procedure "Factorize" for updating the "average_score" attribute for all users.
- **File:** [13-factorize.sql](./alx-backend-storage/0x00-MySQL_Advanced/13-factorize.sql)

14. Log stats – updated
- **Task:** Update the "LogStats" stored procedure to consider a specific range of dates.
- **File:** [14-log_stats.sql](./alx-backend-storage/0x00-MySQL_Advanced/14-log_stats.sql)

15. Get full table
- **Task:** Write a SQL script that creates a stored function "GetFullTable" for returning the full table content.
- **File:** [15-full_table.sql](./alx-backend-storage/0x00-MySQL_Advanced/15-full_table.sql)

---

## Author:

- [`@Josh-techie`]() | Software Engineer Student

  > Reach out to me if you need any help or have any questions.

  <a href="mailto:youssef.abouyahia@e-polytechnique.ma">
  	<img alt="Feel free to contact me" src="https://img.shields.io/badge/-Ask_me_anything-blue?style=flat&logo=Gmail&logoColor=white&link=mailto:youssef.abouyahia@e-polytechnique.ma&color=3d85c6" />
  </a>
  <span> | </span>
    <a href="https://www.linkedin.com/in/youssef-abouyahia/">
        <img alt="Linkedin Profile" src="https://img.shields.io/badge/-Linkedin-0072b1?style=flat&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/youssef-abouyahia/" />
    </a>
    <span> | </span>
    <a href="https://twitter.com/JoesephAb">
        <img alt="Twitter Profile" src="https://img.shields.io/badge/-Twitter-0072b1?style=flat&logo=Twitter&logoColor=white&link=https://twitter.com/JoesephAb&color=1DA1F2" />
    </a>
