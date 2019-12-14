# Intro to Graph Databases Series

## [Episode #4 - Episode #4 - (RDBMS+SQL) to (Graphs+Cypher)](https://www.youtube.com/watch?v=NH6WoJHN4UA&list=PL9Hl4pk2FsvWM9GWaguRhlCQ-pa-ERd4U&index=3)

**Ready to build your application with Neo4j? This video introduces you to the three key steps: creating the model, loading data, querying. Much of the episode covers moving from RDBMS to Graphs. As David Meza from NASA says, "I love Neo4j because I can explore relationships faster than you can say SQL JOIN."**

First steps to using Neo4j:

+ Create your model
+ Load data
+ Query

Neo4j is intended to be an ACID complaint transactional DB. There exist several **language drivers** that allow to query Neo4j. Also, to increase performance there exist **Native Server Side Extensions** that hard code how to traverse graphs rather than letting **cypher query optimizer** decide how to traverse them.

**Polyglot persistence** is an application architecture where different types of DB sit along side others to best suit the type of data and operations. 

Although in many cases RDBs are the best option, in many others, consistency in RDBs is too hard to maintain. As the number of tables and number of foreign keys grows, ER diagrams and join querys become cumbersome. With normalization and size increases, performance degrades for DBs and relational DB developers.

**Cypher is optimized for graphs and readability**. Queries are easy to read in Cypher. This is advantageous for the on-boarding of new team members.

Northwind, the famous canonical data base, is better as a graph. 

Neo4j querying is based on pointer arithmetic rather than index lookups.

Schema migrations are unnecessary on GDBs. Adding additional properties on nodes and relationships on the fly is more convenient.
