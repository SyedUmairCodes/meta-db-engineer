# Relations in data
Data stored in isolation and disconnected from the rest is useless. It must have relations with other data so that it can be used for meaningful information and insights.

Data stored in one table can be related to data stored in another one.  The user details of a person can be linked to multiple details in the orders column of an online store’s database that lists all of the orders of that person.

Two or more people can share the same details like the first or last name so identifying a person in the database is done through a uniquely generated ID that is also called the primary key of the table.

Database engineers use these primary keys to connect different tables together. The primary of the customer table becomes the foreign key in the orders table since it’s from another table.

In the orders table, you can filter and see only the orders placed by the given customer ID. 
