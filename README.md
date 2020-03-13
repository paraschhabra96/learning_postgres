# LEARNING POSTGRES
My journey to learning postgres

## Some Thoughtful Questions

### What is the difference between Primary Key and Unique constraint?
There are no major differences between the primary key and unique constraint in terms of providing functionality to avoid duplicate values. However, both things serves different use cases in terms of database design. A primary key in table helps the application to identify a unique tuple in the table. Usually this is a field which is relevant to the application's context, whereas a unique constraint is merely used for avoiding duplicate values on a field. For ex. If you are creating a student management system for a school, in a table with student details, a primary key would be roll no. ( relevant to the student's management system of the school ) whereas email id of the student could be set with a unique constraint to avoid duplicate values on this field.  
Ref: https://www.geeksforgeeks.org/difference-between-primary-key-and-unique-key/

## Video Links
https://www.youtube.com/watch?v=qw--VYLpxG4&t=7528s

## Web Links
