# ICA-4

**Description of Datasets.titanic**

This dataset describes information about the passengers on the Titanic such as the age, sex, fare amount, and those who did and did not survive.

Q#1: Which passengers were minors (<18)?
       
       SELECT name,
              sex,
              age
       FROM datasets.titanic
       WHERE age<=18 
       ORDER BY age DESC
       LIMIT 100

       
Q#2: Which passengers were adults (>18)?

       SELECT name,
              sex,
              age
       FROM datasets.titanic
       WHERE age>18 
       ORDER BY age DESC
       LIMIT 100


Q#3: Which passengers under 50 years old did not survive?

       SELECT name,
              sex,
              age
       FROM datasets.titanic
       WHERE age<50 AND survived='0'
       ORDER BY age ASC
       LIMIT 50


Q#4: Which passengers over 50 years old survived?

       SELECT name,
              sex,
              age
       FROM datasets.titanic
       WHERE age>50 AND survived='1'
       ORDER BY age ASC


Q#5: Which passengers equal to or under 50 years old survived?

       SELECT name,
              sex,
              age
       FROM datasets.titanic
       WHERE age<=50 AND survived='1'
       ORDER BY age ASC
       LIMIT 50
   


