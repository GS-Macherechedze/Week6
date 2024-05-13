# Week 6 Assignment: CREATE, ALTER & DROP TABLE

This week, we'll establish a foundation for working with databases by creating, modifying, and removing tables using SQL. We'll focus on the music collection scenario to practice these essential skills.

## Learning Objectives:

By the end of this week, you'll be able to:

Write SQL statements to CREATE tables with specified columns and data types.
Use ALTER TABLE to modify existing tables by adding or removing columns.
Utilize DROP TABLE to permanently remove a table from the database.

__________________________________________________________________________________________________
## Instructions (Read and follow instructions)

1. Open MySQL WorkBench or any SQL Management Tool and Import the file/database 
2. Write SQL scripts to answer all questions below. 
3. Save, Export and rename the file to solution.sql Click to play : (https://www.youtube.com/watch?v=fX4-YiXxTn0 )
4. Add file solution.sql to the same repo.
__________________________________________________________________________________________________

Imagine you're building a database to manage a music collection. We'll create a table to store information about songs, then modify it, and finally remove it when it's no longer needed.

## Write SQL commands to achieve the following: 

We don't have a table for songs yet. Let's create one named "Songs" with columns for "Title" (text), "Artist" (text), and "Genre" (text).
After creating the table, you realize you also want to store the song's "Release Year". Use ALTER TABLE to add a new column named "ReleaseYear" of type INTEGER.
Let's say you decide "Genre" isn't necessary for your current needs. Use ALTER TABLE again to remove the "Genre" column.
You no longer need the "Songs" table entirely, you can use DROP TABLE to permanently remove it.
