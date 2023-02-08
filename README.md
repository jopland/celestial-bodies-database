# celestial-bodies-database
this project, you will build a database of celestial bodies using PostgreSQL.
Rules for celestial bodies database
Let’s look at the guidelines we need to follow for this project in order to build acceptable tables.

These are the requirements that we must fulfill while creating the tables:

The database should have at least 5 tables.
There must be a table of the galaxy (≥ 6 rows), star (≥ 6 rows), planet (≥ 12 rows), and moon (≥20 rows).
Each table should have at least 3 rows and 3 columns.
The galaxy, star, planet, and moon tables should each have at least 5 columns.
A primary key should be included in each table. The naming standard for primary key columns should be table_name_id. The moon table, for example, should include a primary key column called moon_id.
Each table should have a name column.
The INT data type must be used in at least two columns that are not the primary or foreign keys.
The NUMERIC data type must be used at least once.
The TEXT data type must be used at least once.
The BOOLEAN data type must be used in at least two columns.
At least 2 columns per table should not accept NULL values.
At least 1 column from each table should be required to be UNIQUE.
Each star should have a foreign key that references one of the rows in galaxy.
Each planet should have a foreign key that references one of the rows in star.
Each moon should have a foreign key that references one of the rows in planet.
Each foreign key column should have the same name as the column it is referencing.
