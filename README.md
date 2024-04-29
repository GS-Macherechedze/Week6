# Week 6 Assignment: CREATE, ALTER & DROP TABLE

Imagine you're building a database to manage a music collection. We'll create a table to store information about songs, then modify it, and finally remove it when it's no longer needed.
## Write SQL commands to achieve the following: 
We don't have a table for songs yet. Let's create one named "Songs" with columns for "Title" (text), "Artist" (text), and "Genre" (text).
After creating the table, you realize you also want to store the song's "Release Year". Use ALTER TABLE to add a new column named "ReleaseYear" of type INTEGER.
Let's say you decide "Genre" isn't necessary for your current needs. Use ALTER TABLE again to remove the "Genre" column.
You no longer need the "Songs" table entirely, you can use DROP TABLE to permanently remove it.
