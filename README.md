# Recipe-Knowledge-Graph-GraphRAG-System

This project builds an **AI-powered recipe discovery system** using **Knowledge Graphs, Neo4j, and GraphRAG (Retrieval-Augmented Generation)**.

The system enables users to query recipes using **natural language**, such as:

* *"Vegetarian Italian dishes under 30 minutes"*
* *"Mexican cuisine using onion and green chilies under 60 minutes"*

Instead of traditional keyword search, the system uses a **graph database and LLM reasoning** to retrieve recipes based on ingredients, cuisines, dietary restrictions, cooking time, and ingredient substitutions.

---

# Project Overview

The project follows a **multi-stage pipeline**:

1. **Data Preprocessing**

   * Clean and merge recipe datasets
   * Normalize ingredients and tags
   * Generate a unified dataset for graph creation

2. **Knowledge Graph Construction**

   * Extract entities and relationships using LLMs
   * Build a graph containing recipes, ingredients, cuisines, tags, users, and reviews

3. **Neo4j Graph Database**

   * Store the knowledge graph in Neo4j
   * Use Cypher queries for efficient relationship traversal

4. **GraphRAG Question Answering**

   * Extract entities from user queries
   * Generate Cypher queries
   * Retrieve graph data
   * Use an LLM to produce grounded natural language answers

5. **Streamlit Application**

   * Interactive UI for recipe discovery
   * Users can search using ingredients or natural language queries

This architecture enables **semantic recipe search and explainable AI recommendations**. 

---

# Key Features

* Knowledge Graph with **8 node types and 10 relationship types**
* Graph database powered by **Neo4j**
* **LLM-based knowledge extraction**
* **GraphRAG pipeline** for grounded responses
* Interactive **Streamlit demo application**
* Natural language recipe discovery

---

# Dataset

The dataset contains:

* **231K recipes**
* **1.1M+ user reviews**
* **35+ cuisines**
* **21 dietary restriction tags**

Recipes are enriched with ingredient relationships, cuisines, nutrition data, and user reviews to enable graph-based reasoning. 

---

# Project Files

```
Recipe_GraphRAG_Project/
│
├── Final_Project_SMA_Recipe_Graphrag_Presentation.pdf
├── demo_app.py
├── kg_triples.json
├── kg_nodes.json
└── README.md
```

---

# Presentation

The full project explanation, architecture, and demo screenshots are available in the presentation:

**📄 Project Presentation:**
See `Final_Project_SMA_Recipe_Graphrag_Presentation.pdf` in this repository.

---

# Tech Stack

* Python
* Neo4j - Cypher Query
* Large Language Models (LLMs)
* Streamlit - Pandas

---

# Team


* Nandini Anand Kumar
* Riju Hariharan
* Varsha Ramesh
* Suryah Vadivel
* Sarvesh Miskin

