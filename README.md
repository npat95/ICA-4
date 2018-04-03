# ICA-4

**Datasets.titanic**

This dataset describes information about the passengers on the Titanic such as the age, sex, fare amount, and those who did and did not survive.

Which passengers were male and over the age of 20?

SELECT name,

        sex,
        
        age
        
FROM datasets.titanic

WHERE age>20 and  sex='male'

ORDER BY age ASC


