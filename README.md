# Week-4-Lab
School Library Books

## Description
As a backend developer you will often be tasked with taking an existing spreadsheet or chunk of data and writing software around it. In this assignment we'll be taking a spreadsheet that records library books and who they are checked out to.

## Objectives

### Learning Objectives

Upon completion of this assignment, you should:

* Understand how to model tables based on existing data
* Understand how to use sql to create tables and query data

### Performance Objectives

After completing this assignment, you be able to effectively use

* Create databases that are normalized and modeled correctly
* Demonstrate understand of sql queries and how to retrieve information out of a database.

## Details

### Deliverables

* A repo containing at least:
  * a database (mdf file) of your data.
  * a schema.sql file that contains the queries to create the tables
  * a queries.sql file that contains the sql queries to generate the answers required.


## Normal Mode

1. Import the librarybooks.csv (librarybooks.csv) file into your database.
2. Analyze the imported data and design a new database that will hold this same information into seperate tables (i.e. Nomarilzation)
3. Create the tables in your database using sql to match your diagram
4. Create queries to populate your tables from the librarybooks.csv table that you imported
5. Answer the following questions:
  1. How many books are there total in the library?
  2. Which books are currently checked out?
  3. How many students are there?
  4. How many books are in each category?
  5. How many books are checked out by category?
  6. Which books will be returned in December?
  7. Which books are missing authors?
 

## Hard Mode

Complete Normal Mode and answer the following:

1. The students ages are correct, but their dob year isn't (though their month and day are). Can you correct their dob?
2. What is the distribution of books by publication date by decade?
3. How many people have P.O. boxes as an address?
4. Split the students name into a firstname and lastname column.

## Additional Resources

* Read [SQL Course](http://sqlcourse.com/) and [SQL Course 2](http://sqlcourse2.com/) 
* Look over [SQL Zoo](http://sqlzoo.net/)

