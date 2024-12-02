# Graph Theory Overview

This document explores two key topics in graph theory:

1. **Direct vs. Undirected Graphs**
2. **Weighted vs. Unweighted Graphs**

---

## Direct vs. Undirected Graphs

### **Directed Graphs (Digraphs)**
- **Definition**: A graph where edges have a direction, meaning they go from one vertex to another specific vertex.
- **Representation**: Represented as ordered pairs `(u, v)`, where `u` is the starting vertex, and `v` is the ending vertex.
- **Examples**:
  - Social networks (e.g., Twitter, where "follows" is a one-way relationship).
  - Road systems with one-way streets.

### **Undirected Graphs**
- **Definition**: A graph where edges have no direction, implying a two-way relationship between vertices.
- **Representation**: Represented as unordered pairs `{u, v}`, meaning both `u` and `v` are connected without any specific direction.
- **Examples**:
  - Friendships in social networks (e.g., Facebook, where relationships are mutual).
  - Road systems with two-way streets.

---

## Weighted vs. Unweighted Graphs

### **Weighted Graphs**
- **Definition**: A graph where each edge is assigned a weight or cost, often representing distance, time, or capacity.
- **Usage**:
  - In **transportation networks**, weights can denote distances or travel times.
  - In **network flows**, weights can represent bandwidth or capacity.
- **Examples**:
  - A map where edges represent roads, and weights are distances between locations.

### **Unweighted Graphs**
- **Definition**: A graph where all edges are treated equally, with no weights or costs associated.
- **Usage**:
  - Suitable for scenarios where connections are binary (either present or absent).
- **Examples**:
  - A friendship network where edges simply indicate a connection between people.

---
