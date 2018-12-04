# Boyce-Codd Normal Form

Before learn abouy BCNF, 1st we have to learn about some other topics.

## Super key / Prime Attribute

If a column or key is a part of primary id, then it will be called super key. The primary id itself is a super key obviously. Prime attribute is the same as super key.

## Non-Prime attribute

The keys other than super key / prime attribute are called Non-prime attribute.

So there are 2 rules to maintail for have BCNF

1. It should maintain 3NF
2. No prime attribute can be dependent on the non-prime attribute

## Example

![Database7](./assets/database7.png)

Lets see the above table. Here the primary key is `student_id + subject`. So they are the prime keys and the non-prime key is professor. But lets see, we can get the subject name from the professor name. That means, a prime key is dependent on the non-prime key. So it doesn't maintain BCNF

## Solution

So the same solution. Break the table into two. One has the attributes (student_id, subject) and another (professor_id, subject, professor_name). Then it maintain BCNF properly.