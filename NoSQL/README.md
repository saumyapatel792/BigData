# MongoDB and Neo4j Lab Exercises

## Overview

This repository contains practical exercises demonstrating the use of MongoDB and Neo4j databases. The exercises cover CRUD operations, aggregation pipelines, graph database operations, graph traversal, indexing, schema flexibility, and comparison between document and graph databases.

---

## Objectives

- Learn MongoDB CRUD operations.
- Perform MongoDB Aggregation Framework queries.
- Demonstrate MongoDB schema flexibility.
- Create and use indexes in MongoDB.
- Learn Neo4j graph database concepts.
- Create nodes and relationships using Cypher.
- Perform graph traversals and shortest path queries.
- Build a simple recommendation engine.
- Compare MongoDB and Neo4j implementations.

---

# Software Requirements

- Ubuntu / Windows / WSL
- Docker Desktop
- MongoDB Community Edition
- MongoDB Shell (mongosh)
- Neo4j Community Edition
- Neo4j Browser
- Visual Studio Code

---

# Project Structure

```
MongoDB-Neo4j-Lab/
│
├── README.md
├── mongo_exercise.txt
├── mongo_aggregation.txt
├── neo4j_exercise.txt
├── screenshots/
│   ├── mongodb/
│   └── neo4j/
└── reports/
```

---

# MongoDB Exercises

## Topics Covered

- Database Creation
- Collection Creation
- Insert Operations
- Query Operations
- Update Operations
- Delete Operations
- Aggregation Framework
- Schema Flexibility
- Indexing
- Text Search

### CRUD Operations

- insertOne()
- insertMany()
- find()
- updateOne()
- updateMany()
- deleteOne()
- deleteMany()

### Aggregation Operators

- $match
- $group
- $project
- $sort
- $unwind
- $lookup
- $setWindowFields

---

# Neo4j Exercises

## Topics Covered

- Create Nodes
- Create Relationships
- Update Nodes
- Delete Nodes
- Graph Traversal
- Recommendation Engine
- Shortest Path
- Graph Visualization

### Cypher Commands

- CREATE
- MATCH
- RETURN
- SET
- DELETE
- DETACH DELETE
- shortestPath()

---

# MongoDB vs Neo4j Comparison

| MongoDB | Neo4j |
|----------|--------|
| Document Database | Graph Database |
| BSON Documents | Nodes & Relationships |
| Flexible Schema | Flexible Schema |
| Aggregation Pipeline | Graph Traversal |
| Best for Product Catalog | Best for Social Networks |

---

# Learning Outcomes

After completing this lab, students will be able to:

- Create MongoDB databases and collections.
- Perform CRUD operations.
- Execute aggregation queries.
- Understand schema flexibility.
- Create indexes for efficient querying.
- Model graph data in Neo4j.
- Create and query graph relationships.
- Find shortest paths.
- Build recommendation queries.
- Compare document and graph databases.

---

# Results

### MongoDB

- Successfully performed CRUD operations.
- Executed aggregation pipelines.
- Created indexes.
- Demonstrated schema flexibility.

### Neo4j

- Created user nodes.
- Created FOLLOWS relationships.
- Performed graph traversals.
- Found shortest paths.
- Generated friend recommendations.

---

# Advantages

## MongoDB

- Flexible schema
- Easy scalability
- Fast document retrieval
- Powerful aggregation framework

## Neo4j

- Excellent relationship handling
- Fast graph traversal
- Efficient recommendation systems
- Natural representation of connected data

---

# Conclusion

The MongoDB and Neo4j laboratory exercises provided practical experience with two different NoSQL database models. MongoDB demonstrated efficient document storage, CRUD operations, aggregation, indexing, and schema flexibility. Neo4j demonstrated graph modeling, relationship management, graph traversal, shortest-path analysis, and recommendation queries. The comparison highlighted that MongoDB is well suited for document-oriented applications, while Neo4j is ideal for highly connected data such as social networks and recommendation systems.

---

