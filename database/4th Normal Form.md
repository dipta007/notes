# 4th Normal Form

To maintain 4th Normal Form, one has to maintain 2 rules -

1. It should maintain 3NF
2. It shouldn't have Multi valued dependency

## Multi-Valued Dependecy

If these 3 conditions are met, then the table has multi-valued dependency  

1. If there are 3 columns A, B & C, then B and C both dependent on A, where A is the primary key
2. Table must have more than 2 columns
3. There is no relation between B and C

## Example

![Database8](./assets/database8.png)

Lets have a look on the above table. Here primary id is `s_id`. So lets see, if they meet all the three conditions.

1. course and hobby both are dependent on s_id
2. The table has more than 2 columns
3. course and hobby has no inter relationship

So the table has multi-valued dependency, hence it doesn't have 4NF. You can think, what is the problem with the above approach. The problem is for the s_id=1 we need 4 rows to represent like the below table.

![database9](./assets/database9.png)

So its a bad design

## Solution

For all the others, the solution is to decompose the table in two tables. One is for the Student_course(s_id, course) and other one is for Student_hobby(s_id, hobby)