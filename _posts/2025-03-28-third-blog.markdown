---
layout: post
title:  "DBS101 Unit 3"
date:   2025-03-28 18:23:50
categories: Blog
tags: featured
image: /assets/article_images/2014-11-30-mediator_features/night-track.JPG
image2: /assets/article_images/2014-11-30-mediator_features/night-track-mobile.JPG
---
Mastering Database Systems: Unit 2 Must-Knows
ACID: The Cornerstones of Reliable Transactions
Atomicity: Makes sure transactions either succeed entirely or leave nothing behind—exactly what operations like payments or bookings require.

Consistency: Enforces data validity using constraints such as primary keys and foreign keys.

Isolation: Prevents concurrent transactions from interfering with each other.

Durability: Ensures data outlives system crashes.
Why it matters: Not negotiable in banking, reservations, or any system where data correctness is life-or-death.

SQL: The Language of Data
Schemas Designing:
Create tables with constraints (i.e., primary keys for uniqueness, foreign keys for joining).
Use normalization to minimize redundancy.

Core Operations:
CRUD: Create, read, update, and delete information in a efficient and quick manner.
Joins: Merge data from multiple tables to expose relationships (i.e., linking users to their booked flights).
Aggregates: Roll up data with averages, counts, or grouping (i.e., calculating average fares per flight class).
Advanced Techniques:
Subqueries: Nest queries to filter or examine data in layers.

Handling Missing Data: Use functions to handle missing values gracefully.

Transactions & Security
Commit/Rollback: Commit transactions or roll them back on failure for integrity.

Authorization: Restrict access to protect sensitive data (e.g., limiting who sees payment details).

Why Unit 2 Matters
Build Robust Systems: Being ACID-compliant makes transactions fail-safe. 

Uncover Data Insights: Master SQL queries, joins, and data analysis like a pro.

Design for Scale: Use normalization and constraints to create efficient, adaptable databases.

By mastering these principles, you’ll craft databases that power everything from e-commerce platforms to airline systems—secure, scalable, and bulletproof.


Key in 50 Words:
Unit 2 introduces ACID principles of error-proofed transactions, SQL for schema definition and querying data (joins, aggregates, subqueries), and transaction security. Master these to build databases that handle real-world needs—think banks or bookings—accurately, at scale, and with rock-solid reliability.