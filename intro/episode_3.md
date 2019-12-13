# Intro to Graph Databases Series

## [Episode #3 - Property Graph Model](https://www.youtube.com/watch?v=NH6WoJHN4UA&list=PL9Hl4pk2FsvWM9GWaguRhlCQ-pa-ERd4U&index=3)

**Teaches how the property graph represents data, starting with a basic example: Dan Loves Ann. Discusses nodes, relationships, and properties on both nodes and relationships. Labels, directionality, and Cypher CREATE statements are also introduced.**

With graph modeling **white board model is the physical model**. That is, there is a lack of translation friction and it is faster to build apps and easier to maintain them.

Neo4j works with property graphs. This means that it store properties along with the nodes and relationships. Node properties can be used to define types of nodes. 

Noe4j is schema optional. It has the flexibility to add new relationships and properties on the fly.

A simple way to understand graph models:

+ nodes are nouns
+ properties of nodes are adjectives
+ relationships are verbs
+ properties of relationships are adjectives

Cypher is a declarative language to create and query GDBs. In Neo4j relationships are directional

CREATE (:Person{name:"Ann"}) -[:LOVES]-> (:Person{name:"Dan"})

MATCH (:Person{name:"Ann"}) -[:LOVES]-> (:Person{name:"Dan"})

To return relationships regardless of the direction:

MATCH (:Person{name:"Ann"}) -[:LOVES]- (:Person{name:"Dan"})

