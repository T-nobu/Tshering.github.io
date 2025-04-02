---
layout: post
title:  "DBS101 Unit 1"
date:   2025-03-02 14:34:25
categories: Blog
tags: regular

---


### Topic : Data users and data Administration

A database is an organized collection of structured information, typically stored electronically in a computer system. It allows for efficient data retrieval, updating, and management. A Database Management System (DBMS) is a software system that enables users to interact with the database, providing tools for data storage, retrieval, and manipulation.

Advantages of Database Systems
Database systems are essential for managing large, valuable datasets accessed by multiple users and applications:

Data abstraction: Simplifying complex data structures for users.

Concurrency control: Allowing multiple users to access data simultaneously without conflicts.

Data integrity: Ensuring data accuracy and consistency through constraints and rules.

Applications of Database Systems
Database systems are widely used across various industries:

Banking and finance: For transaction processing and customer information management.

Social media: Storing user profiles, posts, and interactions.

Sales: Managing customer orders, inventory, and sales data.

Navigation systems: Storing and retrieving geographic data.

### Topic : Data Models and Database Design

A data model is a collection of conceptual tools for describing data, data relationships, and consistency constraints. There are four main types of data models:

Entity-Relationship Model (ER Model): Represents data as entities and relationships between them.

Semi-Structured Data Model: Used for data that doesn’t fit into rigid structures, such as XML or JSON.

Object-Based Data Model: Combines data and methods (functions) into objects, similar to object-oriented programming.

Relational Model: Represents data in tables (relations) with rows and columns.

Relational Model
The relational model, introduced by Edgar F. Codd in the late 1960s, revolutionized database systems by separating the logical and physical layers of data. In this model:

Data is stored in tables (relations).

Each table has columns (attributes) and rows (records).

SQL (Structured Query Language) is used to perform operations like creating, reading, updating, and deleting data.

Database Abstraction
Database systems use data abstraction to hide the complexity of data structures from users. There are three levels of abstraction:

Physical level: Describes how data is stored on the disk.

Logical level: Describes what data is stored and the relationships between data.

View level: Provides a simplified view of the database for specific users or applications.

Database Languages
Database systems use two main types of languages:

Data Definition Language (DDL): Used to define and modify the database schema (e.g., creating tables).

Data Manipulation Language (DML): Used to retrieve, insert, update, and delete data (e.g., SQL queries).