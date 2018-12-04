# 2nd Normal Form

There are 2 rules to follow in 2NF

1. It needs to maintain 1NF
2. It should not have partial dependency

## What is Partial Dependency

Let's think of a table which contains score of a student like below.

![database4](./assets/database4.png)

here `score_id` is the primary key. But think of it, `student_id + subject_id` makes more sense for the primary id as there are many to many relationship with student_id and subject_id

### Many to Many relationship

* One student can take as many subjects as he wants.  
* One subject can be opted by the as many as want

So there is many to many relationship between student_id and subject_id

### Partial Dependency
Now for our previous example, teacher column is dependent on onlu subject_id. So it is call partial dependcy. 

## Solution
So what should be done is that, we have to remove the teacher column and it should be saved on another table or on the subject table.

