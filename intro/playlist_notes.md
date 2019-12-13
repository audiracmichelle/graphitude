# Intro to Graph Databases Series

## Intro to Graph Databases (Episode #1 - Evolution of DBs)[https://www.youtube.com/watch?v=5Tl8WcaqZoc&list=PL9Hl4pk2FsvWM9GWaguRhlCQ-pa-ERd4U&index=2&t=11s]

**Takes you through the evolution of databases, as the shape of our data and volume of data has changed - from RDBMS to key value, to document DBs, to Neo4j.**

First, databases were punch tapes. Then came tables and relational databases. These were **normalized to eliminate duplication** and inconsistencies. 

With normalization, fields reference **auto-generated numerical foreign keys**. Foreign keys are difficult to understand and maintain; they also make complicated joins indispensable for querying.

ACID support provides the certainty that after data is committed into a database, the data will be **accessible for future queries**.

It is expensive to find data. Although indices make **lookups faster**, the query time of join queries increases provided that index lookups are performed for each table. 

The NoSQL revolution and the creation of key value interfaces made evident that it was time to care less about the discrete bits of data and more about the relationships between
data.

The beginning of GDBs (graph data bases) features the birth of the real "relational databases". GDBs provide intuitive data models, faster queries and **better ability do adapt to changes**.

Neo4j brings **data integrity** to GDBs. 

